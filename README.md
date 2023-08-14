<div align="center">
    <img src="https://github.com/GoldenPearls/study_cs/assets/97003348/7eb5def4-90b1-497d-927c-7b271dfc4bc9" width="50%"/>
</div>

<h1> Exploring Knowledge and Organizing CS Studies </h1> 

---
<h3> ✒️ 무엇을 위한 저장소인가..</h3>  

- CS지식에 대한 것
- 그 외에 프로그래밍 공부하면서도 기억해야 하는 지식 기록하기 위한 용도의 저장소로 사용
- 블로그에 기록도 좋지만 한 번에 보기 위한 정리 저장소

<h3> 📜 나만의 공부 규칙 [≡] ✍(・⺫・‶) </h3>

- 하루에 1~2개씩이라도 꾸준히 업데이트 하기
- 한 번보고 끝내는 것이 아닌 계속 반복적으로 보고 기억하기
-  Github는 preview가 같이 안돼서 불편하니 자세히 적는건 velog에 해서 링크 연결, 여기는 간단 요약 적어두기

# 알고리즘과 자료구조
<details><summary style="color:skyblue">BigO</summary>    

### [🔭 자세한 설명](https://velog.io/@prettylee620/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EB%B3%B5%EC%9E%A1%EB%8F%84)
### 🪄 간단한 설명
- 알고리즘의 실행 시간이나 공간 복잡도를 표현하는 표기법 중 하나로 Big O 표기법은 알고리즘의 성능을 분석하고 비교하는 데 사용된다.
- Big O는 주어진 알고리즘이 입력 크기에 대해 얼마나 효율적으로 실행되는지를 나타낸다.
- 이 표기법은 주로 **최악의 경우** 시나리오에서 알고리즘의 실행 시간이 어떻게 증가하는지를 나타낸다.
- Big O는 함수 형태로 표기되며, 일반적으로 `O(f(n))`으로 표기되며, 여기서 `f(n)`은 입력 크기 `n`에 대한 함수

예를 들어, `O(1)`은 상수 시간을 의미하며, 입력 크기에 관계없이 실행 시간이 일정하다. `O(n)`은 선형 시간을 의미하며, 입력 크기에 비례하여 실행 시간이 증가한다.
`O(n^2)`은 이차 시간을 의미하며, 입력 크기의 제곱에 비례하여 실행 시간이 증가하며 이와 같이 Big O 표기법을 사용하여 **알고리즘의 효율성을 분석하고 개선하는 데 도움을 준다.**  
    
</details>

# 그 외
### 🗒️ 스택 트레이스 + nullpointException이 일어나는 이유
<details><summary style="color:skyblue">[🔭 자세한 설명]</summary>    

> 일단 출처
https://jaehoney.tistory.com/51
https://okky.kr/articles/338405

#### 개념
- 프로그램이 시작된 시점부터 현재 위치까지의 메서드 호출 목록
- 예외가 어디서 발생했는지 알려주기 위해 JVM을 생성
#### 필요 이유
- 스택 트레이스를 읽는 능력은 선택이 아닌 필수
- 무턱대고 오류내용을 복붙하고 해결을 위한 코드도 복붙한다면 직면한 문제는 해결할 수 있지만 발전 없이 머물러 있게 됨
- 강사님도 항상 강조하는 내용
#### 그렇다면 읽는 법?
```JAVA
public class StackTraceTest 
{
	public static void main(String[] args) 
	{
		one();
	}
	
	public static void one()
	{
		two();
	}

	public static void two()
	{
		three();
	}
	
	public static void three()
	{
		Integer.parseInt("abcde");
	}
}
```
![](https://velog.velcdn.com/images/prettylee620/post/0bc51219-6345-49e0-899d-cfc22c9ee627/image.png)
1. 스택트레이스는 에러가 발생된 시점부터 프로그램이 시작된 시점까지 거슬러 올라가면서 출력되기 때문에 **먼저 실행된 메서드가 가장 아래**
2. 나도 보려고 노력하지만 겁먹기 마련이다. 대부분 처음 시작하는 분들이 그렇더라 
3. 하지만 에러의 진정한 원인은 가장 아래쪽(초기)에 있는 `Caused by:`로 시작되는 줄부터 아래로 세줄이면 충분
```java
Caused by: java.lang.NullPointerException
     at com.mycompany.service.impl.PortalManagerImpl.deleteMenuItem(PortalManagerImpl.java:603)
     at com.mycompany.service.impl.PortalManagerImpl.deletePortal(PortalManagerImpl.java:358)
```
4. 위의 내용은 com.mycompany.service.impl.PortalManagerImpl' 클래스의 `deletePortal` 메소드 358라인에서 같은 클래스의 `deleteMenuItem`메소드를 호출했는데 해당 메소드 603번 째 줄에서 널포인터 예외가 발생했다라고 해석
> **okky의 질문**
![](https://velog.velcdn.com/images/prettylee620/post/44408d1c-8078-468d-b5c6-1a9b2be04488/image.png)
**okky의 답변**
`deleteMenuItem()`은 재귀 호출을 하는 메서드라서 혼동이 되신 것 같습니다. 스택트레이스의 인용하신 부분은 "603번 째 줄에서 deleteMenuItem()을 호출할 때"가 아니라 "호출된 deleteMenuItem() 메서드의 내부의 603번 째 줄"임</br>
🐇 좀 더 자세히 설명하자면,
deleteMenuItem() 메서드 내부에서 getMenuItems(item.getPortal().getId(), item.getId()) 메서드를 호출하려고 합니다. 이때, item이 null인 경우 NullArgumentException이 발생하고 예외가 던져집니다.

5. `PortalManagerImpl` 클래스 소스
```java
if (item == null) {
    throw new NullArgumentException("item");
}

//중간 생략
List<PortalMenu> children = getMenuItems(item.getPortal().getId(), item.getId()); // 603번째 줄

for (PortalMenu child : children) {
    deleteMenuItem(child);
 }
 ```
#### 그렇다면..? 널포인트 exception 원인은?
- 많은 수의 지원자들이 `children`이나 `item.getId()` 등에 널값이 들어간 것 같다고 답했다고 한다. 이론적으로 해당 라인에서 널값이 들어갈 수 있는 모든 경우의 수는,

> 1. children
> 2. item
> 3. item.getPortal()
> 4. item.getPortal().getId()
> 5. item.getId()

- 이 중 적어도 두 가지, 즉 2번 혹은 3번으로 가능성을 바로 좁히지 못한다면 그것은 널포인터 예외의 의미를 정확하게 파악하지 못하고 있기 때문이라고 한다.

> 널포인터 예외는 단순하게 변수에 널값이 들어가서 생기는 오류가 아니다. `널포인터 예외`는 **명확하게 객체의 널레퍼런스에 대해 메소드 호출이나 필드 참조 등의 작업을 했을 때 발생하는 문제**라는 것을 이해한다면 이런 문제는 곧바로 원인을 좁힐 수 있어야 한다.

- 즉, 1번의 경우처럼 단순히 변수에 널값을 할당하는 것만으로는 절대로 널포인터 예외가 날 수 없다. 그리고 만일 4 번 `item.getPortal().getId()`이나 5번 `item.getId()`이 널이라면 이는 널 레퍼런스에 대한 호출이 아니라 널값을 `getMenuItems`라는 **메소드의 인자로 넘기는 것 뿐이기 때문에 역시 널포인터 예외의 원인이 될 수 없다.**

- 물론 `getMenuItem` 메소드 안에서 **해당 인자에 대한 널체크 없이 값을 사용하다가 예외가 날 수도 있겠지만** 이 경우엔 절대로 트레이스 상에 **굵은 글자로 표시된 603번 째에서 예외를 뿌리지 않는다.**

- 그렇다면 남은 가능성은 2번 'item'이 널이거나 3번 'item.getPortal()'이 널인 경우뿐인데, 'item' 변수는 위에서 널체크를 하기 때문에 603번 째 줄에서 절대로 널값을 가질 수 없다. 그렇기 때문에 답은 3번이 되는 것

#### 읽어보면 좋은 글
[개발은 암기과목이 아닙니다](https://okky.kr/questions/311337)

#### 논외 Visual Studio와 Visual Studio Code
> 스택 트레이스 를 읽는 법을 찾다가 알게 된 것인데... 둘은 완전히 다르다는 것
Visual Studio는 IDE(통합 개발 환경)이며 Visual Studio Code는 Sublime Text 및 Atom과 같은 리치 텍스트 편집기로
도구 간의 차이점은 IDE와 텍스트 편집기 그 이상이라고 한다.
IDE는 코드 작성, 편집, 디버깅 및 실행을 위한 강력한 도구로 텍스트 편집기에서는 코드를 작성하고 편집할 수만 있다. 코드를 실행하거나 자동으로 실행되도록 플러그인을 다운로드하려면 텍스트 편집기에서 나가야 할 수도 있다고 함.. 깊게 공부 안하고 돌리기만 해서... 몰랐다.
