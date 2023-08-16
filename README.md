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

[🔭 자세한 설명](https://velog.io/@prettylee620/Big-O) </br>
🪄 간단한 설명
- 알고리즘의 실행 시간이나 공간 복잡도를 표현하는 표기법 중 하나로 Big O 표기법은 알고리즘의 성능을 분석하고 비교하는 데 사용된다.
- Big O는 주어진 알고리즘이 입력 크기에 대해 얼마나 효율적으로 실행되는지를 나타낸다.
- 이 표기법은 주로 **최악의 경우** 시나리오에서 알고리즘의 실행 시간이 어떻게 증가하는지를 나타낸다.
- Big O는 함수 형태로 표기되며, 일반적으로 `O(f(n))`으로 표기되며, 여기서 `f(n)`은 입력 크기 `n`에 대한 함수

예를 들어, `O(1)`은 상수 시간을 의미하며, 입력 크기에 관계없이 실행 시간이 일정하다. `O(n)`은 선형 시간을 의미하며, 입력 크기에 비례하여 실행 시간이 증가한다.
`O(n^2)`은 이차 시간을 의미하며, 입력 크기의 제곱에 비례하여 실행 시간이 증가하며 이와 같이 Big O 표기법을 사용하여 **알고리즘의 효율성을 분석하고 개선하는 데 도움을 준다.**  
    
</details>

<details><summary style="color:skyblue">Linked List(연결리스트)</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EC%97%B0%EA%B2%B0%EB%A6%AC%EC%8A%A4%ED%8A%B8) </br>
🪄 간단한 설명
- 노드의 포인터 부분으로 서로 연결시킨 리스트 데이터 포인터
- 노드에는 데이터 값을 저장하는 data와 링크, 포인터의 역할을 하는 next가 있다.
- 연결리스트는 이어진 메모리 공간이 아닌 불특정 공간에 존재하여 탐색은 선형시간이 걸림
- 상황에 따라 배열보다 빨라질 수 있는 노드 삽입과 삭제

</details>


<details><summary style="color:skyblue">Array(배열)</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EB%B0%B0%EC%97%B4array) </br>
🪄 간단한 설명
- 배열은 위치만 알면, 읽을 때 데이터에 빠르게 접근 가능
- 많은 자료를 읽어내려고 할 때 배열이 좋다. 배열의 요소의 개수 상관없이 Random하게 읽어내니까
- Reading은 인덱스를 이용해서 O(1)이지만 Searching, Insert, Delete는 O(n)
- 배열은 접근 연산을 제외하면, 탐색, 삽입, 삭제 연산에 대해 비교적 효율적이지 않으므로, 알고리즘 설계 시 이러한 연산의 효율성 고려할 것

</details>

<details><summary style="color:skyblue">Stack과 Que</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EC%8A%A4%ED%83%9D%EA%B3%BC-%ED%81%90) </br>
🪄 간단한 설명
- 스택과 큐는 우리의 상상에만 존재, 실제로 프로그래밍 언어들에서는 존재하지 않음
- 스택과 큐는 일종의 규칙으로 결국 배열 위에 어떤 규칙을 설정한 모습
- 스택은 LIFO(Last in First Out)으로 팬케이크를 먹는다고 할 때 가장 늦게 올린 것을 먼저 먹는 형식과 비슷
- 큐는 FIFO(First in First Out)으로 버스 타기 위해 줄 설 때 맨 앞 사람이 가장 먼저 타는 것과 비슷

</details>

<details><summary style="color:skyblue">Array vs ArrayList vs LinkedList 차이</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/Array-vs-ArrayList-vs-LinkedList-차이)

🪄 간단한 설명
- **Array**는 index로 빠르게 값을 찾는 것이 가능함 </br>
- **ArrayList**는 데이터를 찾는데 빠르지만, 삽입 및 삭제가 느림  </br>
- **LinkedList**는 데이터의 삽입 및 삭제가 빠름
- array와 ArrayList의 차이는 array의 경우 우리가 선언 할 때 크기를 지정하고 크기를 확장 시 제한 적이다. 하지만 ArrayList는 크기 유동적이라서 add를 하면 공간 자체 유동적이다.

![image](https://github.com/GoldenPearls/study_cs/assets/97003348/57cd8664-b2e1-4c4c-a0f6-301948efa256)
![image](https://github.com/GoldenPearls/study_cs/assets/97003348/6bbf6507-9c95-4c4a-824a-860b29b0ac05)


</details>



# 공부방법

<details><summary style="color:skyblue"> 컴퓨팅적 사고 방식</summary> 
	
[🔭 자세한 설명 :테오님 블로그](https://velog.io/@teo/computational-thinking)
</details>

# 그 외
###  스택 트레이스 + nullpointException이 일어나는 이유
<details><summary style="color:skyblue">[🔭 자세한 설명]</summary>    

> 일단 출처
https://jaehoney.tistory.com/51
https://okky.kr/articles/338405

**개념**
- 프로그램이 시작된 시점부터 현재 위치까지의 메서드 호출 목록
- 예외가 어디서 발생했는지 알려주기 위해 JVM을 생성
**필요 이유**
- 스택 트레이스를 읽는 능력은 선택이 아닌 필수
- 무턱대고 오류내용을 복붙하고 해결을 위한 코드도 복붙한다면 직면한 문제는 해결할 수 있지만 발전 없이 머물러 있게 됨
- 강사님도 항상 강조하는 내용
**그렇다면 읽는 법?**
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
**그렇다면..? 널포인트 exception 원인은?**
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
</details>

# 관련 정리된 링크들
- [ [IT 개발자와 일할 때 필요한 모든 개발지식] A to Z 자료 모음집 By 그랩](https://www.grabbing.me/IT-A-to-Z-By-1e1fbc981b7c4c03ac44943085ac8304)
: 웬만한 CS 지식 집합체 IT 분야 종사자라면 봐야함

- [[IT 개발자와 일할 때 필요한 모든 개발지식] A to Z 자료 모음집 By 그랩의 어려운 IT 용어 정리](https://www.grabbing.me/IT-e042e5f23b2147878ead089c97ef3c77#35a8ac77dfa84380bdd9d1c4e29e84d3)
: 위와 똑같은 곳으로 어려운 IT 용어 모음

- [신입 개발자 전공 지식 & 기술 면접 백과사전](https://gyoogle.dev/blog/)
: 기술 면접에 대한 정리가 체계적으로 잘되어 있는 편

- [신입 개발자 전공 지식 & 기술 면접 백과사전](https://github.com/WooVictory/Ready-For-Tech-Interview)
: 위의 웹사이트 GITHUB 버전

- [다른 사람이 면접시 물어본 것을 VELOG에 정리한 것](https://velog.io/@matisse/%EA%B8%B0%EC%88%A0%EB%A9%B4%EC%A0%91-%EC%A7%88%EB%AC%B8-%EC%A0%95%EB%A6%AC-CS)
: 3년전 글이긴 한데 정리가 잘되있어서 나도 나중에 면접시 저런식으로 정리해야 겠다를 생각함

- [READY FOR TECH INTERVIEW](https://github.com/WooVictory/Ready-For-Tech-Interview)
: 이 곳은 신입 혹은 주니어 개발자에게 필요한 지식을 정리하는 GITHUB

- [Technical Interview Guidelines for Beginners](https://github.com/JaeYeopHan/Interview_Question_for_Beginner)
: 시작하는 주니어 개발자들을 위한 기초 지식 정리한 GITHUB

- [Backend-Interview-Question](https://github.com/ksundong/backend-interview-question)
: 백엔드 개발자 입사시 질문, 예상질문 GITHUB
