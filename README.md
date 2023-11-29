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

<details><summary style="color:skyblue">Array(배열)</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EB%B0%B0%EC%97%B4array) </br>
🪄 간단한 설명
- 배열은 위치만 알면, 읽을 때 데이터에 빠르게 접근 가능
- 많은 자료를 읽어내려고 할 때 배열이 좋다. 배열의 요소의 개수 상관없이 Random하게 읽어내니까
- Reading은 인덱스를 이용해서 O(1)이지만 Searching, Insert, Delete는 O(n)
- 배열은 접근 연산을 제외하면, 탐색, 삽입, 삭제 연산에 대해 비교적 효율적이지 않으므로, 알고리즘 설계 시 이러한 연산의 효율성 고려할 것

</details>

</details>

<details><summary style="color:skyblue">동적계획법과 분할정복</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EB%8F%99%EC%A0%81-%EA%B3%84%ED%9A%8D%EB%B2%95%EA%B3%BC-%EB%B6%84%ED%95%A0%EC%A0%95%EB%B3%B5-ih96sv90) </br>
🪄 간단한 설명

1. 동적 계획법
>동적 계획법으로 문제를 풀 때는 우선 작은 문제부터 해결해나가보는 것이 좋다. 작은 문제들을 풀어나가다보면 이전에 구해둔 더 작은 문제들이 활용되는 것을 확인하게 된다.
- 복잡한 문제를 간단한 여러 개의 문제로 나누어 푸는 방법, 작은 하위 문제의 해를 저장하고 활용하여 중복 계산을 피하며 문제를 해결하는 데 중점을 둔다.
- `상향식 접근법`으로 가장 최하위 해답을 구한 후, 이를 저장하고, 해당 결과값을 이용해서 상위 문제를 풀어가는 방식이다.
- 한 가지 문제에 대해서, 단 한번만 풀도록 만들어주는 알고리즘
- `Memoization` 기법을 사용한다.
-  Memoization (메모이제이션) 이란: 프로그램 실행 시 이전에 계산한 값을 저장하여, 다시 계산하지 않도록 하여 전체 실행 속도를 빠르게 하는 기술

2. 분할정복
> 분할 정복은 주로 큰 문제를 작은 하위 문제로 나누어 해결하는 데 중점
문제를 나눌 수 없을 때까지 나누어서 각각을 풀면서 다시 합병하여 문제의 답을 얻는 알고리즘
`하향식 접근법`으로, 상위의 해답을 구하기 위해, 아래로 내려가면서 하위의 해답을 구하는 방식

- 병합정렬 : 분할(Divide) => 정복(Conquer) => 합병(Merge) 과정을 거친다.
- 퀵정렬 : 기준 데이터 설정, 그 기준보다 큰 데이터와 작은 데이터의 위치를 바꾸면 ?

</details>

<details><summary style="color:skyblue">트리</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%ED%8A%B8%EB%A6%AC%EB%AF%B8%EC%99%84%EC%84%B1-%EC%B6%94%EA%B0%80-%EC%98%88) </br>
🪄 간단한 설명

1. 트리
- 그래프 중 하나로 그래프의 특징처럼 정점과 간선으로 이루어져 있고, 트리 구조로 배열된 일종의 계층적 데이터의 집합
- 트리로 이루어진 집합을 숲이라고 함
- 뿌리가 최상위로 올라감
- 가계도와 같음 ⇒ 단군 할아버지가 A같은 느낌
- 데이터를 순차적으로 저장하지 않는 비선형 구조
- 트리에 서브트리가 있는 재귀적 구조

2. 이진 트리
- 각 노드의 자녀 노드 수 최대 2개인 트리를 의미
- 정 이진 트리 : 모든 노드는 자녀 노드가 없거나 두 개인 트리
- 완전 이진 트리 : 마지막 레벨을 제외한 모든 레벨에서 노드가 빠짐없이 채워져 있고 마지막 레벨은 왼쪽부터 빠짐없이 노드가 채워져 있는 트리
- 포화 이진 트리 : 모든 레벨에서 노드가 빠짐없이 채워져 있는 트리
- 변질 이진 트리 : 모든 부모 노드는 하나의 자녀 노드만을 가짐

3. 이진 탐색 트리
- 이진 탐색이 동작할 수 있도록 고안된 효율적인 탐색이 가능한 자료구조의 일종

4. 트리 순회
- 전위 순회(Pre-Order Traversal) : 현재 노드 방문 => 재귀적으로 왼쪽 서브 트리 순회 => 재귀적으로 오른쪽 서브 트리 순회
- 중위 순회(In-Order Traversal) : 재귀적으로 왼쪽 서브 트리 순회 => 현재 노드 방문 => 재귀적으로 오른쪽 서브 트리 순회회
- 후위 순회(Post-Order Traversal) : 재귀적으로 왼쪽 서브 트리 순회 => 재귀적으로 오른쪽 서브 트리 순회 => 현재 노드 방문

</details>

<details><summary style="color:skyblue">우선순위 큐와 힙의 차이
</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EC%9A%B0%EC%84%A0%EC%88%9C%EC%9C%84-%ED%81%90%EC%99%80-%ED%9E%99%EC%9D%98-%EC%B0%A8%EC%9D%B4) </br>
🪄 간단한 설명
1. 우선순위 큐
- 큐와 유사하지만 우선순위가 높은 아이템이 먼저 처리됨

2. 힙
- 주로 이진 트리 기반으로 구현이 됨
- 트리(tree) : 부모 - 자녀처럼 계층적인 형태를 가지는 구조
- 이진 트리 : 자녀가 최대 두 개인 트리

3. priority queue와 Heap의 관계
- 관계
> 힙(Heap)의 키(key)를 우선순위(priority)로 사용한다면, 힙은 우선순위 큐(priority queue)의 구현체가 된다.
Priority queue = ADT(구현을 설정하지 않고 개념적인 것만 설명)

- 추상 자료형(abstract data type)
**추상 자료형**은 구현 방법을 명시하고 있지 않다는 점에서 자료 구조와 다르다. 비슷한 개념의 추상적 자료 구조는 각 연산의 시간 복잡도를 명기하고 있지만 추상적 자료형에서는 이것조차 명기하지 않는다.
추상 자료형은 인터페이스와 구현을 분리하여 추상화 계층을 둔 것이다. 예를 들어 전기 밥솥을 추상 자료형에 비유한다면 그 속에 들어가는 밥은 자료가 되고, 밥솥에 있는 취사, 예약취사 버튼들과 남은 시간을 표시하는 디스플레이에 어떤 내용들이 표시되어야 하는지를 명기한 것이다.
Heap = data structure(구현까지 있음)
우선순위 큐를 구현하기 위해 다양한 것들이 있겠지만, 힙을 대체로 많이 사용해서 동일시 하는 사람들이 있다.
</details>

# spring
<details><summary style="color:skyblue">AOP</summary>
<details><summary style="color:skyblue">AOP란 무엇인가?</summary>
AOP는 Aspect-Oriented Programming의 약자로, 주요한 비즈니스 로직과 공통적인 부가 기능을 분리하여 관리하는 프로그래밍 패러다임  
</details>

<!-- AOP에 관한 내용 -->
<details><summary style="color:skyblue">AOP의 핵심 개념은 무엇인가요?</summary>
AOP의 핵심 개념은 '관점(Aspect)'입니다. 이는 어플리케이션 전반에 걸쳐 사용되는 부가적인 기능들을 의미하며, 예를 들어 로깅, 보안, 트랜잭션 관리 등이 있습니다. 
</details>

<details><summary style="color:skyblue"> AOP의 장점은 무엇인가요?</summary>
AOP를 사용하면 주요 비즈니스 로직과 부가 기능이 분리되므로 코드의 재사용성과 유지보수성이 향상됩니다. 또한, 공통된 기능을 여러 부분에서 중복해서 구현하지 않아도 되므로 코드 중복을 줄일 수 있습니다.
</details>

<details><summary style="color:skyblue"> AOP에서 핵심 로직과 부가 기능을 어떻게 분리하나요?</summary>
AOP에서는 '어드바이스(Advice)', '포인트컷(Pointcut)', '위빙(Weaving)' 등의 개념을 사용하여 핵심 로직과 부가 기능을 분리합니다. 어드바이스는 부가 기능의 내용을 담고 있고, 포인트컷은 어떤 메소드나 위치에서 어드바이스를 적용할지를 정의합니다. 위빙은 이러한 부가 기능을 실제로 핵심 로직에 적용하는 작업을 의미합니다.
</details>

<details><summary style="color:skyblue"> AOP의 예시를 들어볼까요?</summary>
예를 들어, 트랜잭션 관리는 여러 비즈니스 메소드에서 공통적으로 필요한 기능입니다. AOP를 사용하면 이런 트랜잭션 관리 로직을 핵심 비즈니스 메소드와 분리하여 따로 관리할 수 있습니다. 또 다른 예로 로깅 기능도 있습니다. 핵심 로직의 실행 전후에 로깅을 추가하는 것도 AOP를 통해 간단하게 구현할 수 있습니다.
</details>

<details><summary style="color:skyblue"> AOP가 실제 어떻게 동작하나요?</summary>
AOP는 런타임 시점에 위빙 작업을 통해 부가 기능을 핵심 로직에 적용합니다. 이를 위해서는 프록시(Proxy)라는 중간 객체를 사용합니다. 프록시는 핵심 로직을 호출하기 전에 어드바이스를 실행하고, 그 후에도 필요한 부가 기능을 수행한 후 핵심 로직을 호출합니다.
</details>

<details><summary style="color:skyblue"> AOP를 스프링에서 어떻게 사용하나요?</summary>
스프링 프레임워크는 AOP를 지원하여 개발자가 편리하게 부가 기능을 관리할 수 있도록 도와줍니다. 스프링에서 AOP를 사용하려면 어노테이션을 이용한 설정 방식이나 XML 설정 방식을 선택하여 어드바이스와 포인트컷을 정의하고, 위빙을 설정할 수 있습니다.
</details>

<details><summary style="color:skyblue"> AOP를 사용하면 어떤 상황에서 유용한가요?</summary>
AOP는 주로 다양한 모듈에서 공통으로 사용되는 부가 기능을 분리하여 관리할 때 유용합니다. 트랜잭션 관리, 보안, 로깅 등 여러 곳에서 반복적으로 필요한 기능을 AOP를 통해 중앙에서 관리하면 코드의 효율성과 유지보수성을 높일 수 있습니다.
</details>

<details><summary style="color:skyblue">  AOP를 사용할 때 주의해야 할 점은 무엇인가요?</summary>
AOP를 오용하지 않도록 주의해야 합니다. 너무 많은 부가 기능을 AOP로 분리하면 코드가 복잡해질 수 있으며, 디버깅이 어려울 수 있습니다. 또한, AOP의 성능도 고려해야 합니다. 핵심 로직을 실행하기 전후에 부가 기능을 실행하므로, 불필요한 오버헤드가 발생할 수 있습니다.
</details>
  
</details>

<!-- 스프링을 쓰게 된 계기 이유-->
<details><summary style="color:skyblue"> 스프링을 쓰는 이유</summary>

<details><summary style="color:skyblue"> 프레임 워크의 중요</summary>

  > 💡 프레임워크는 말 그대로 뼈대나 근간을 이루는 코드들의 묶음으로 개발자 능력에 따라 결과 역시 큰 차이를 낳는데 이런상황을 극복하기 위해 나온 것이 프레임워크다. 프레임워크를 이용한다는 것은 프로그램의 기본 흐름이나 구조를 정하고, 모든 팀원이 이 구조에 자신의 코드를 추가하는 방식

즉, 프레임워크의 최대 장점은 개발에 필요한 구조를 이미 코드로 만들어 놓았기 때문에, 실력이 부족한 개발자라 해도 반쯤 완성된 상태에서 필요한 부분을 조립하는 형태의 개발이 가능
</details>

<details><summary style="color:skyblue"> 나오게 된 계기</summary>

> 💡 2000년대 초반부터 시작된 엔터프라이즈급의 개발은 안정된 품질의 개발이 절실했고, 그 결과 많은 프레임워크의 전성시대

spring은 가장 성공한 경량 프레임워크이다.
경량 프레임워크
90년대 말에 복잡한 구동 환경과 하드웨어적인 구성이 필요한 프레임워크의 반대되는 개념으로 등장
특정 기능을 위주로 간단한 jar 파일 등을 이용해서 모든 개발이 가능하도록 구성된 프레임워크
클라이언트 중심, 모바일 중심, Light weight, 생산성, 안전성, 다양한 개발 언어
</details>

<details><summary style="color:skyblue"> 그렇다면 그 많은 것 중에 왜 성공했을까?</summary>
  
1. 복잡함에 반기를 들어서 만들어진 프레임워크로 일반적으로 java클래스와 인터페이스를 이용하는 구조이기 때문에 진입장벽이 높지 않았기 때문이다.
2. 프로젝트의 전체 구조를 설계할 때 유용한 프레임워크로 스프링은 어느 한 분야에 집중하지 않고, 전체를 설계하는 용도로 사용하며 근본적인 사상 자체가 OOP 구조를 뒷받침하고 구조를 설계하는 사상
3. 다른 프레임워크들의 포용으로 다른 프레임워크들은 특정 프레임워크를 채택하면 해당 영역 전체를 수정해야 하는 고질적인 문제가 있으나, 스프링은 다른 프레임워크들과의 통합 지원했기 때문에 최소한의 수정이 가능했다. 스프링의 최대 장점은 기본 뼈대가 흔들지 않고 여러 종류의 프레임워크 혼용해서 사용 가능
4. 개발 생산성과 개발도구의 지원으로 플러그인도 빠른 업데이트 되었기에 별도의 개발도구에 적응 없이도 개발 가능
</details>

<details><summary style="color:skyblue"> 그렇다면 스프링의 특징은..?</summary>
  
1. 제어 역행(IoC, Inversion of Control) 기술
- 이용해 애플리케이션 간의 느슨한 결합을 제어함
2. 의존성 주입(DI, Dependency Injection) 을 통한 객체 간의 관계 구성
- 의존성(dependency)
    - 하나의 객체가 다른 객체 없이 제대로 된 역할을 할 수 없는 것을 말한다.
    - 하나의 객체가 다른 객체의 상태에 따라 영향을 받는 것을 의미
- 주입(Injection)
    - 말 그대로 외부에서 밀어 넣는 것
- 의존성 주입
    - 어떤 객체가 필요한 객체를 외부에서 밀어 넣는다.
- **왜 사용하는 걸까?**
    - 주입을 받는 입장에서는 어떤 객체인지 신경 쓸 필요가 없다.
    - 어떤 객체를 의존하든 자신의 역할은 변하지 않는다.
    - 스프링은 이러한 구조를 만드는데 적합한 구조로 설계되어 있다.
    - `ApplicationContext`라는 존재가 필요한 객체 생성하고 필요한 객체 주입시켜줌
    - `ApplicationContext` 이 관리하는 객체는 빈(bean)이라고 부름

3. 영속성과 관련된 다양한 서비스를 지원함

4. 수 많은 라이브러리와의 연동 기능을 지원함

5. APO의 지원

- 반복적인 코드를 줄이고 핵심 비즈니스 로직에만 집중할 수 있게 해줌
- APO 지원 관련은 여기서 적어둠

6. 트랜잭션의 지원

- 스프링은 이런 트랜잭션의 관리를 어노테이션이나 XML로 설정할 수 있기 때문에 매번 맞는 코드 작성 할 필요 없

7. POJO 방식 프레임워크

- 내부에는 `객체 간의 관계`를 구성할 수 있는 특징을 지님
- 다른 프레임워크와 달리 이 관계 구성 시 **별도의 API를 사용하지 않는** POJO(Plan Old Java Object)의 구성이 가능하도록 제작
- 즉, 일반적인 Java 코드를 이용해서 객체 구성하는 방식을 그대로 스프링에서 사용 가능
- 코드를 개발 시 개발자가 특정 라이브러리나 컨테이너의 기술에 종속적이지 않기 때문에, 생산성에도 유리하고, 코드에 대한 테스트 작업 역시 좀 더 유연하다.

</details>
</details>

<details><summary style="color:skyblue"> IoC란?</summary>

> IoC는 "Inversion of Control"의 약자로, 한국어로는 "제어의 역전"
이는 소프트웨어 디자인 패턴 중 하나로서, 프로그램의 제어 흐름을 역전시켜서 프레임워크 또는 컨테이너가 코드의 실행 흐름을 관리
IoC는 의존성 주입(Dependency Injection, DI)과 밀접한 관련이 있으며, 주로 객체 지향 프로그래밍 환경에서 사용된다.

🪄 핵심개념

1. 제어 역전
- 일반적으로 프로그래밍에서는 개발자가 코드의 흐름과 제어를 결정한다.
- 하지만 IoC에서는 이 제어의 역할이 프레임워크나 컨테이너로부터 개발자로부터 분리되어 제어의 주체가 역전된다.(외부에서 결정)
2. 의존성 주입 (DI)
- 객체들 간의 의존성을 프레임워크나 컨테이너가 주입하는 방식
- 이를 통해 객체 간의 결합도를 낮추고 유연성을 높일 수 있다.

IoC는 코드의 재사용성, 유지보수성, 테스트 용이성 등을 향상시키는 장점을 가지고 있다. </br>
대표적으로 스프링 프레임워크에서는 IoC와 DI를 기반으로 개발자가 애플리케이션의 핵심 비즈니스 로직을 구현하고, 프레임워크가 객체의 생성과 의존성 관리를 담당하도록 하는 것이 핵심 원칙 중 하나이다.
</details>

<details><summary style="color:skyblue"> Bean</summary>

<details><summary style="color:skyblue"> Bean이란</summary>

> 💡 스프링 프레임워크에서 빈은 객체의 인스턴스를 의미한다. 스프링은 객체 지향 프로그래밍의 기본 원칙에 따라 작성된 클래스의 인스턴스를 생성하고 관리하는데 이러한 **인스턴스를 빈**이라고 하며, Bean은 스프링에서 사용하는 POJO 기반 객체다. 
> 스프링 컨테이너는 애플리케이션에서 필요한 빈 객체를 생성하고, 관리하며, 필요한 시점 제공해준다. 빈은 스프링의 IoC 컨테이너의 핵심 개념 중 하나이며, 컨테이너에 의해 생성되고 관리되기 때문에 객체의 생명주기와 의존성 주입등을 효율적으로 관리할 수 있다. 
>
> 스프링에서 빈은 주로 `XML 설정 파일이나 Java Config` 등을 통해 정의하고, 애플리케이션에서 필요한 위치에서 이 빈을 사용하게 된다. 빈은 대부분의 경우 싱글톤으로 생성되어 애플리케이션 전반에 걸쳐 하나의 인스턴스만 유지한다. 그 이유는 **싱글톤 패턴처럼 특정 타입의 Bean을 딱 하나만 만들고 모두 공유해서 사용하기 위함이다**
           
</details>

<details><summary style="color:skyblue">Bean Scope 종류</summary>

  > Bean Scope란? Bean의 사용범위를 말한다. 그리고 request, session, global session은 MVC 웹 어플리케이션에만 사용함
  
1. sigleton
: 해당 Bean에 대해 IoC컨테이너에서 `단 하나의 객체`로만 존재한다. 가장 많이 사용

2. prototype
:  해당 Bean에 대해 `다수의 객체`가 존재할 수 있다.

3. request
: 해당 Bean에 대해 `하나의 HTTP Request의 라이프사이클`에서 단 하나의 객체로만 존재한다.

4. session
: 해당 Bean에 대해 하나의 HTTP Session의 라이플사이클에서 단 하나의 객체로만 존재

5. global session
: 해당 Bean에 대해 하나의 Golbal HTTP Session의 라이프사이클에서 단 하나의 객체로만 존재한다.

> Scope들은 Bean으로 등록하는 클래스에 어노테이션으로 설정해줄 수 있다.

```java
import org.springframework.context.annotation.Scope;
import org.springframework.stereotype.Service;
 
@Scope("prototype")
@Component
public class UserController {
}
```
</details>
</details>

# 프로그래밍 언어
## JAVA
<details><summary style="color:skyblue"> Call by value vs Call by Reference과 기본형과 참조형</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/Call-by-value-vs-Call-by-Reference)

🪄 간단한 설명
- **Call by Value**란 인자의 실제 값을 복사하여 함수의 매개변수에 전달하는 방식으로 실제로 메모리 주소 자체 전달이 아니며, 대표적으로 자바는 Call by Value만 지원한다.
- **기본형**의 경우 실제 데이터 값이 복사 되며, 값의 복사 => 별도의 메모리 공간 => 원본 값의 보존 순서로 진행된다.
- **참조타입**의 경우 객체의 주소값이 복사되는데 동작방식은 참조의 복사 => 동일한 객체에 대한 참조 => 객체 변경의 영향 순서로 진행된다.
- 그렇다면 반대로 Call by Reference란 뭘까?
- `Call by Reference`란? 함수에 인자를 전달할 때 인자의 실제 메모리 주소를 전달하는 방식이며, 인자의 실제 메모리에 접근하고 수정할 수 있다. Call by Reference의 특징이란 stack영역에 생성된다. 또한 참조형은 heap 영역에 저장한다.

</details>


<details><summary style="color:skyblue"> Reflection </summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/Reflection)

🪄 간단한 설명
- 자바에서 런타임시 **클래스의 정보를 분석하고 조작하는 기법**으로 컴파일 타임에는 알 수 없는 클래스를 동적으로 로딩하여 사용하거나, 클래스의 메소드, 필드, 생성자 등의 정보를 동적으로 분석할 수 있는 강력한 기능 제공
- 자바에서 이미 로딩이 완료된 클래스에서 또는 다른 클래스를 동적으로 로딩하여 구체적인 타입을 알지 못하더라도 생성자, 멤버 필드, 그리고 멤버 메소드를 사용할 수 있는 기법이다.
- `객체를 통해서` 클래스의 패키지 정보, 접근 지정자, 부모 클래스, 어노테이션 등을 얻을 수 있다.
- 즉, 핵심은 컴파일 타임이 아니라 런타임에 동적으로 컴파일 타임에는 알 수 없는 클래스를 **특정 클래스의 정보를 객체화**하여 **분석 및 추출해낼 수 있는 동적 프로그래밍 기법**이다.

</details>

<details><summary style="color:skyblue"> 인터페이스와 인터페이스와 추상클래스의 차이점 </summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4%EC%99%80-%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4%EC%99%80-%EC%B6%94%EC%83%81%ED%81%B4%EB%9E%98%EC%8A%A4%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90)

🪄 간단한 설명
**인터페이스란?**
- 인터페이스는 상호작용을 위해서 미리 정의된 약속으로, 서로 다른 모듈이나 시스템을 연결하고 기능을 사용하기 위한 도움미 역할을 하는 것이다. 마치 컴퓨터를 키기 위해 전원을 누르는 것과 같은 것으로 여기서는 전원 버튼이 인터페이스로서 컴퓨터를 켜는 역할을 한다. 실생활에서 무의식 가운데 쓰는 것들이 인터페이스
- 예를 들어 A라는 함수라는 호출하면 B라는 결과 도출되는 것이 인터페이스다. 즉, 컴퓨터의 파워 전원 버튼, 변기의 레버 등이 인터페이스가 될 수 있다.
- 즉, 인터페이스란 서로 다른 시스템이나 기능을 연결하여 사용할 수 있게 도와준다.
- 인터페이스는 인터페이스를 구현하는 모든 클래스에 대해 특정한 메소드가 반드시 존재하도록 강제한다.
🤔 그렇다면.. 덩치가 큰 인터페이스 API는 뭘까? API와 인터페이스와의 연계
- Application Programming Interface의 약자로 제조사가 그 기능을 개발에 잘 쓰게 만들기 위해서는 사용자한테 제공해주는 프로그램이나 코드의 세트를 의미하는 인터페이스
- 구글 인앱 API를 사용하여 개발한다면 우리의 앱과 구글 인앱 결제 사이를 이어주는 인터페이스가 API가 되는 것이고 이 중간에 있는 것들은 뭐든지 인터페이스
</details>

<details><summary style="color:skyblue"> Wrapper Class와 오버라이딩 vs 오버로딩 + final 키워드 </summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/Wrapper-Class%EC%99%80-%EC%98%A4%EB%B2%84%EB%9D%BC%EC%9D%B4%EB%94%A9-vs-%EC%98%A4%EB%B2%84%EB%A1%9C%EB%94%A9-final-%ED%82%A4%EC%9B%8C%EB%93%9C-ty2fqdfn)

🪄 간단한 설명
**Wrapper Class란?**
- 자바에서 Wrapper Class는 기본 데이터 타입을 객체로 다루기 위해 사용되는 클래스들을 의미
- 사용 용도는 보통 객체로 저장해야 할 때, 매개변수로 객체가 요구될 경우, 객체 간의 비교가 필요한 경우 등이 있다.

**오버라이딩과 오버로딩**
- 오버라이딩 : 자식 클래스가 부모 클래스로부터 상속받은 메서드를 재정의하는 것, 상속받은 메서드와 같은 이름, 같은 반환 타입, 같은 매개변수를 가져야 한다. `다형성` 실현하는 데 필수적
  ```java
class Animal {
    public void sound() {
        System.out.println("동물 소리");
    }
}

class Dog extends Animal {
    @Override
    public void sound() {
        System.out.println("멍멍");
    }
}
```
- 오버로딩 : 같은 이름의 메서드를 여러개 가질 수 있게 하되, 매개변수의 타입이나 개수를 다르게 하는 것으로 코드의 가독성과 재사용성을 높이는 데 도움이 된다.
```java
class Calculator {
    public int add(int a, int b) {
        return a + b;
    }

    public double add(double a, double b) {
        return a + b;
    }
}
```

</details>

<details><summary style="color:skyblue"> non-static 멤버와 static 멤버</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/non-static-%EB%A9%A4%EB%B2%84%EC%99%80-static-%EB%A9%A4%EB%B2%84)

🪄 간단한 설명
1. non-static 멤버 = instance 멤버
- 객체 별로 다른 상태를 유지할 수 있으며, 객체 생성시 마다 메모리를 할당하고 non-static 멤버는 객체의 인스턴스를 통해서만 접근 가능하다.
- 공유되지 않는다.
```java
public class MyClass {
    // Non-static 필드
    int instanceField;

    // Non-static 메소드
    void instanceMethod() {
        // ...
    }
}
```
2. static 멤버 = class 멤버
- 해당 클래스의 모든 인스턴스에 의해 공유되며, 한 인스턴스에서 static 멤버의 값을 변경하면, 그 변경사항이 모든 인스턴스에 영향을 미친다.
- 프로그램 시작시 한 번만 메모리에 할당되며, 클래스 이름을 통해 접근 가능하다.
```java
Dog.bark(); // static 메소드 호출 => 생성하지 않아도 사용 가능

```

</details>

<details><summary style="color:skyblue">객체 지향 프로그래밍 vs 절차 지향 프로그래밍</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EA%B0%9D%EC%B2%B4-%EC%A7%80%ED%96%A5-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D-vs-%EC%A0%88%EC%B0%A8-%EC%A7%80%ED%96%A5-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D)

🪄 간단한 설명

**1. 객체 지향 프로그래밍**

- 객체 지향 프로그래밍은 OOP(Object Oriented Programming)이라고도 한다.
- 프로그래밍에서 필요한 데이터를 추상화시켜 상태와 행위를 가진 객체를 만들고 그 객체들 간의 유기적인 상호작용을 통해 로직을 구성하는 프로그래밍 방법이다.

**2. 객체 지향 프로그래밍의 특징**

**1) 캡슐화(Encapsulation)**
서로 연관된 데이터와 함수를 함께 묶어 외부와 경계를 만들고 필요한 인터페이스만을 밖으로 드러내는 기법
결합도가 낮아지고 재사용 용이
인터페이스가 단순화
인터페이스를 제외한 세부 내용이 정보 은닉되어 외부 접근 제한
외부 모듈의 변경으로 인한 파급 효과가 적음
정보 은닉과 관계가 깊으며 변경 발생시 오류의 파급 효과가 적음
결합도 down/ 응집도 up[2020.3회, 4회]

**2) 상속성(Inheritance)**
상위 클래스의 속성과 메서드를 하위 클래스에서 재정의 없이 물려받아 사용하는 기법
재사용성을 높이는 중요한 개념

**3) 다형성(Polymorphism)**
하나의 메세지에 대해 각 객체가 가지고 있는 고유한 방법으로 응답할 수 있는 능력
상속받은 여러 개의 하위 객체들이 다른 형태의 특성을 갖는 객체로 이용될 수 있는 성질
오버로딩, 오버라이딩
ex. ‘+’ 연산자의 경우 숫자 클래스에서는 덧셈, 문자 클래스에서는 문자열의 연결 기능

**4) 정보은닉(Information Hiding)**
코드 내부 데이터와 메서드를 숨기고 공개 인터페이스를 통해서만 접근이 가능하도록 하는 코드 보안 기술
필요하지 않은 정보는 접근할 수 없도록 하여 한 모듈 또는 하부 시스템이 다른 모듈에 구현에 영향을 받지 않게 설계됨(고려되지 않은 영향인 Side-Effect들은 최소화)
설계에서 은닉되어야 할 기본 정보로는 IP주소와 같은 물리적 코드, 상세 데이터 구조 등이 존재
필요하지 않은 정보는 접근할 수 없도록 하여 한 모듈 또는 하부시스템이 다른 모듈의 구현에 영향을 받지 않게 설계되는 것을 의미한다.
정보은닉은 모듈 독립성을 갖추게 해줘 변화에 따른 수정 가능
모듈들 사이의 독립성을 유지시키는 데 도움이 된다.

**5) 관계성(Relationship)**
종류로는 연관화, 분류화, 집단화, 일반화, 특수화가 있음
두 개 이상의 엔터티 형에서 데이터를 참조하는 관계로 나타내는 기법

**3. 객체지향 설계 원칙(SOLID)**
- 단일 책임의 원칙(SRP- Single Responsibility Principle): 하나의 클래스는 하나의 목적을 위해 존재
- 개방 폐쇄 원칙(OCP – Open Close Principle)**: 소프트웨어의 구성요소는 확장에는 열려있고, 변경에는 닫혀있어야**하는 원칙
- 리스코프 치환의 원칙(LSP –Liskov Subsitution) : 서브 타입(상속받은 하위 클래스)은 어디서나 자신의 기반 타입(상위 클래스)로 교체할 수 있어야 한다는 원칙
- 인터페이스 분리의 원칙(ISP-Interface Segregation Principle) : 클라이언트는 자신이 사용하지 않는 메서드와 의존관계를 맺으면 안된다. 클라이언트가 사용하지 않는 인터페이스 때문에 영향을 받아서는 안된다.[2020 4회]
- 의존성 역전의 원칙(DIP-Dependency Inversion Principle): 실제 사용관계는 바뀌지 않으며, 추상을 매개로 메세지를 주고받음으로써 관계를 최대한 느슨하게 만드는 원칙
</details>

<details><summary style="color:skyblue"> String, StringBuilder, StringBuffer</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/qofg42hq)

🪄 간단한 설명
**1. String**
- String은 불변하는 문자열을 나타낸다.
- String 객체에 저장된 문자열은 생성된 후에 변경할 수 없다.
- 불변성 때문에 String은 문자열 연산이 많은 경우 **비효율적**일 수 있다.
- 예를 들어, 반복적인 문자열 연결은 매번 새로운 String 객체를 생성하기 때문에 메모리 사용과 성능에 부담을 줄 수 있다. 즉, 메모리 공간의 낭비가 발생하고 성능이 떨어진다.
- 불변성은 String을 스레드 안전(thread-safe)하게 만듭니다.
- 문자열 연산이 적고, 조회가 많은 상황에서 쓰기 좋다.

**2. StringBuilder**
- StringBuilder는 가변적인 문자열을 나타낸다.
- 이 클래스를 사용하면 기존의 문자열 내용을 변경하거나 추가할 수 있어, 반복적인 문자열 수정 작업에서 높은 성능을 제공
- StringBuilder는 스레드 안전하지 않다.
- 따라서 멀티 스레드 환경에서는 주의해서 사용해야 한다
- 성능: StringBuilder는 String보다 문자열 연산(추가, 수정, 삭제 등)에 있어 훨씬 효율적
- StringBuilder는 동기화를 고려하지 않는 상황에서 사용.(Thread를 사용하지 않는 상황.) 문자열 연산이 많은 싱글 쓰레드 환경.

**3. StringBuffer**
- 가변성 (Mutability): StringBuffer도 StringBuilder와 마찬가지로 가변적인 문자열을 다룹니다. StringBuilder와 비슷한 API를 제공
- StringBuffer의 주요 차이점은 스레드 안전하게 설계되었다는 것
- 이는 StringBuffer의 모든 주요 연산이 동기화(synchronized)되어 있다는 의미
- StringBuffer는 StringBuilder에 비해 느릴 수 있다.
- 이는 동기화로 인한 오버헤드 때문이다. 따라서 단일 스레드 환경에서는 StringBuilder가 선호
- StringBuffer는 동기화가 필요한 멀티 쓰레드 환경에서 사용. 문자열 연산이 많은 멀티 쓰레드 환경.


</details>

<details><summary style="color:skyblue"> thread 스레드r</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/thread-%EC%8A%A4%EB%A0%88%EB%93%9C)

🪄 간단한 설명
🥕 스레드
- 멀티태스킹의 해결책 : 스레드(thread)의 특징
- 프로세스는 한 개 이상의 스레드 가질 수 있다.
- 한 프로세스 안에서 여러 개의 작업을 동시에 실행하기 위해 이 여러 개의 하나하나를 맡아 줄 것이 필요한데 그것이 스레드
- CPU에서 실행되는 단위(unit of execution)
- 예전에는 프로세스가 cpu에서 실행되는 단위였다면… 지금은 스레드가 cpu가 실행되는 단위
- 같은 프로세스의 스레드들끼리 `컨텍스트 스위칭`은 가볍다.
- 스레드들은 자신들이 속한 프로세스의 `메모리 영역을 공유`
- 그렇기 때문에 3번인 컨텍스트 스위칭이 가볍고 두 번째로는 같은 프로세스 안의 스레드들끼리는 데이터 공유가 쉽다.

</details>



# 운영체제
<details><summary style="color:skyblue"> 프로세스, 스레드, 멀티태스킹, 멀티스레딩, 멀티프로세싱, 멀티프로그래밍</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4-%EC%8A%A4%EB%A0%88%EB%93%9C-%EB%A9%80%ED%8B%B0%ED%83%9C%EC%8A%A4%ED%82%B9-%EB%A9%80%ED%8B%B0%EC%8A%A4%EB%A0%88%EB%94%A9-%EB%A9%80%ED%8B%B0%ED%94%84%EB%A1%9C%EC%84%B8%EC%8B%B1-%EB%A9%80%ED%8B%B0%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%EA%B3%BC-%EC%8A%A4%EB%A0%88%EB%93%9C%EB%A5%BC-%EB%A7%8E%EC%9D%B4-%EC%93%B8%EC%88%98%EB%A1%9D-%ED%95%AD%EC%83%81-%EC%84%B1%EB%8A%A5%EC%9D%B4-%EC%A2%8B%EC%9D%84%EA%B9%8C)

🪄 간단한 설명
- **단일 프로세스**란 한 번에 하나의 프로그램만 실행
- 단일 프로세스의 단점 해결책으로 멀티 프로그래밍 등장
- **멀티 프로그래밍**은 여러 개의 프로그램을 메모리 올려놓고 동시에 실행
- 하지만, cpu 사용시간이 길어지면 다른 프로세스 대기시간 너무 길어짐
- 그것의 해결책으로 멀티태스킹 등장
- **멀티 태스킹**은 프로세스는 한 번 cpu 사용시 `아주 짧은 시간(=quantum)`만 cpu 실행
- 그럼에도 아쉬움이 남은점들.. 특히 프로세스의 `컨텍스트 스위칭`은 무거우며, 독립된 메모리 공간을 가져서 데이터 공유가 어려움
- 그것의 해결책으로 멀티스레딩이 나옴
- **멀티스레딩**이란 같은 프로세스를 가진 스레드들은 같은 메모리 공간을 공유하되, 스레드들 만의 고유한 영역도 있다. 스레드가 가장 작은 실행 단위가 됨
- **멀티프로세싱**은 두 개 이상의 프로세서나 코어를 활용하는 시스템을 말한다.

</details>

<details><summary style="color:skyblue"> 스레드를 많이 쓸수록 항상 성능이 좋아질까..?</summary>
멀티스레딩 환경에서 쓰는 것을 말함

1. 당장 보통 드는 생각은 스레드를 많이 쓰면 쓸수록 동시에 처리할 수 있는 프로그램 수도 늘어나니 애플리케이션의 성능이 전체적으로 좋아질 것 같다라고 생각할 수 있음
2. 그러나, 여기에 전제가 깔림
3. 전제 : 해당 어플리케이션은 `더 작은 작업들로 잘게 쪼개서 동시에 실행이 가능한 성격`의 애플리케이션

**순차적 애플리케이션**

1. `순차적`으로 실행되어야 하는 애플리케이션이라면.. 그래서 잘게 쪼개서 동시에 실행하기 매우 어려운 성격의 애플리케이션이라면 **스레드를 많이 쓰려고 해도 실제 사용할 수 있는 스레드 수는 제한이 생김**
2. 코어에서 실행되던 스레드가 다른 스레드로 바뀔 때마다,`context switching`을 하는데, 이런 스위칭 작업도 **CPU 코어에서 실행**되게 되는 작업
3. 즉, 코어에서 `스위칭 작업`을 처리하는 동안에는 **애플리케이션 코드가 실행되지 않음**
    1. `overhead` : 이때, 스위칭 작업을 위해 소비되는 **CPU time**은 애플리케이션과 직접적인 관련은 없지만 멀티스레딩으로 동작하기 위해 필요하기 때문에 간접 방식이라고 부름
4. 위의 지식을 바탕으로 CPU의 코어 수는 고정되어 있는데 스레드 수를 계속 늘리게 되면 한 코어에서 경합해야하는 스레드의 수는 더 늘어나기 때문에 **OVERHead**도 많아짐 ⇒ 한계

**CPU bound, I/O bound 관점**

**CPU bound 애플리케이션**

1. cpu를 많이 쓰기 떄문에 코어 수와 비슷한 수준 이상으로 스레드 수를 늘려봤자 이점이 없다.
2. 오히려 각 코어에서 경합하는 스레드 수가 많아질 수

록히 context switching 때문에 overhead만 더 많아져서 성능에 안 좋은 영향

**I/O bound 애플리케이션**

1. I/O 작업이 많기 때문에 CPU가 놀고 있는 시간이 많다.
2. 코어 수보다 두~세배 늘려주는 것이 overhead가 늘긴 해도 코어들을 좀 더 효율적으로 사용 가능하기에 성능 이점이 있음
3. 물론 너무 많이 늘리면 안좋음
	
</details>

<details><summary style="color:skyblue"> 비동기 맥락에 따른 의미</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EB%B9%84%EB%8F%99%EA%B8%B0%EC%97%90%EC%84%9C-%EA%B0%81-%EB%A7%A5%EB%9D%BD%EC%97%90-%EB%94%B0%EB%A5%B8-%EC%9D%98%EB%AF%B8%EB%A5%BC-%EC%84%A4%EB%AA%85)

🪄 간단한 설명

**동기[sysncronous | 동시에 일어나는]**
- 순차적으로 실행
- 코드 한줄, 한줄 실행이 끝난 뒤 다음 코드로 넘어가는 처리 방식
- 동시에 일어난다는 뜻을 가진다.
- 어떤 것을 요청하면 이에 대한 결과가 동시에 일어난다는 뜻입
- 요청을 한다면 얼마나 시간이 걸려도 그 자리에서 결과가 주어져야 한다.
- 즉, 여러 작업(task)들을 순차적으로 실행하도록 개발

**비동기[asyncronous | 동시에 일어나지 않음]**
- 동시에 일어나지 않음을 의미
- 어떤 것에 대한 요청에 의한 결과가 동시에 일어나지 않음을 의미
- 요청해도 이를 즉시 처리하지 않아 결과가 이후에 나오게 된다.
- 즉, 여러 개의 요청을 동시에, 독립적으로 처리할 수 있다는 의미입니다.
- 실행이 오래걸리는 코드라면, 효율성 측면에서 비동기로 실행하는 것이 더 좋다.
- 코드 실행 후, 완료 여부와 관계없이 다음 코드로 넘어가는 처리 방식[다른 작업을 동시에 수행]

**그렇다면.. 비동기가 좋기만 할까?**
1. 동기 방식
- 매우 직관적. 어떤 작업을 실행하면 끝날때까지, 그리고 순차적으로 진행하기 때문
- 하지만, 결과가 주어질 때까지 아무것도 못하고 대기해야 한다.
2. 비동기 방식
- 결과가 주어지기 전까지 다른 작업을 할 수 있기 때문에 효율적
- 하지만 동기 방식에 비해 직관적이지 못하고 복잡하다는 단점

</details>

<details><summary style="color:skyblue"> 컴퓨터 구조와 운영체제를 알아야 하는 이유 - 운영체제 개념</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EC%BB%B4%ED%93%A8%ED%84%B0-%EA%B5%AC%EC%A1%B0%EC%99%80-%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C%EB%A5%BC-%EC%95%8C%EC%95%84%EC%95%BC-%ED%95%98%EB%8A%94-%EC%9D%B4%EC%9C%A0-%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C-%EA%B0%9C%EB%85%90)

🪄 간단한 설명

**컴퓨터 근간을 알게 되면 좋은 점**
1. 문제 해결 능력

> 내가 만든 프로그램이 어떻게 동작하는지를 알아야 한다. 컴퓨터를 미지의 대상이 아니라 분석의 대상으로 봐야 하는 능력을 길러야 한다. 

즉, `컴퓨터의 내부 동작`을 들여다봐야 한다. 그러니까 내가 만든 코드가 **컴퓨터의 가장 밑단부터 어떻게 차근차근 실행되는 지**를 알 수 있어야 한다. 개발자들이 말하는 분석하는 능력을 길러야 한다는 의미가 여기서부터 시작된다고 볼 수 있다.

2. 성능, 용량, 비용
개발에서 가장 중요한 이야기 중 하나, 애플리케이션 개발 시 대규모 트래픽 처리라던지.. 빠른 처리라던지.. 등등과 같이 중요한 것이다.

**컴퓨터의 구조는 2가지로 나뉜다**
> 첫 번째, 컴퓨터가 이해하는 2가지 정보

1. 데이터
2. 명령어

> 두 번째, 컴퓨터의 네 가지 핵심 부품

1. cpu
- 관리자 역할을 하는 운영체제의 커널이 프로그램을 메모리에 올려 프로세스로 만들면 일꾼은 CPU가 처리
- `ALU(산술 논리 연산장치)` : 계산기, 계산을 위한 회로들의 모음
- `레지스터` : CPU 내부의 작은 임시기억저장장치, CPU는 자체적으로 저장할 방법이 없기 떄문에 레지스터를 거쳐 데이터 전달
- `제어장치` : 제어 신호를 내보내고, 명령어를 해석하는 장치, 데이터 처리를 위한 순서 ㄷ결정
2. 메모리
- `현재 실행되는` 프로그램의 **명령어와 데이터를 저장**하는 부품
- 프로그램이 실행되려면 메모리에 저장되어 있어야 한다.
- 메모리에 저장된 값의 위치는 주소로 알 수 있다.
3. 보조기억장치
- RAM, SSD, USB Memory, CD Rom, 하드디스크, SD 카드
- 전원이 꺼져도 보관할 프로그램을 저장하는 부품으로 메인보드 외부에 존재
- (주 기억장치보다)용량도 더 크고 가격이 저렴
4. 입출력장치
- 컴퓨터 외부에 연결되어 컴퓨터 내부와 정보를 교환 할 수 있는 부품

> 핵심 부품을 연결해주는 2가지
1. 메인 보드
2. 시스템 버스

**운영체제란?**
- 자원을 관리하는 특별한 **프로그램**
- `실행 중인 프로그램`[=프로세스]을 관리하는 특별한 **프로그램**

> 운영체제 또한 특별하지만 프로그램이기 때문에 마찬가지로 메모리에 저장, 다만 특별하기에 커널 영역에서 실행

> 운영체제를 알아야 하는 이유는?

**🌻 운영체제는 프로그램을 위한 프로그램이다.**

운영체제는 **사용자를 위한 프로그램이 아니다.** 그저 컴퓨터를 이용하기만 할 때는 알지 몰라도 상관없다. 만들고 실행하는 프로그램에게 여러 기능을 주는 프로그램이 운영체제이다.

> 프로그램을 만드는 개발자는 운영체제를 알아야 한다. **어떻게 내가 만들고자 하는 프로그램이 도움을 받고 있는지 동작하는지를 이해 해야한다.**
> 

**🌻 문제 해결 능력 - 오류 메세지에 대한 깊은 이해**

- 오류 메세지를 내보내는 근원적인 주체는 운영체제로 볼 수 있다. 그렇기 때문에 **내가 만들고자 하는 프로그램이 도움받고 있는 운영체제를 깊게 이해하면 오류 메세지에 대해 깊게 이해할 수 있다.**

> 운영체제는 즉, 그 속에서 ***프로그램이 실행할 수 있도록 하는 환경을 제공***
>
</details>

<details><summary style="color:skyblue"> 인터럽트, 시스템 콜, 유저모드, 커널모드 들의 프로그래밍과의 관계</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EC%9D%B8%ED%84%B0%EB%9F%BD%ED%8A%B8-%EC%8B%9C%EC%8A%A4%ED%85%9C-%EC%BD%9C-%EC%9C%A0%EC%A0%80%EB%AA%A8%EB%93%9C-%EC%BB%A4%EB%84%90%EB%AA%A8%EB%93%9C-%EB%93%A4%EC%9D%98-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%EA%B3%BC%EC%9D%98-%EA%B4%80%EA%B3%84)

🪄 간단한 설명

**User mode와 Kernel mode**
1. user mode
우리가 개발하는 프로그램은 일반적으로 유저모드에서 실행
2. user mode ⇒ Kernel mode
프로그램 실행 중에 인터럽트(interrupt)가 발생하거나 시스템 콜(system call)을 호출하게 되면 커널 모드로 전환
3. Kernel mode
방금 전까지 실행 중이던 프로그램의 현재 CPU 상태를 저장함
나중에 마저 실행하기 위해
커널이 인터럽트나 시스템 콜을 직접 처리한다. 즉, CPU에서 커널 코드가 실행됨
처리가 완료되면 중단됐던 프로그램의 직전의 CPU 상태를 복원
4. Kernel mode ⇒ user mode
다시 통제권을 프로그램에게 반환
5/ user mode
프로그램이 이어서 실행된다.
6. 커널(kernel)
운영체제의 핵심
시스템의 전반을 관리/감독하는 역할
하드웨어와 관련된 작업을 직접 수행

**Interrupt**
시스템에서 발생한 다양한 종류의 이벤트 혹은 그런 이벤트를 알리는 매커니즘이자 어떤 신호가 들어왔을 때 `CPU를 잠깐 정지`시키는 것'

**시스템 콜의 개념**
프로그램이 OS 커널이 제공하는 서비스를 이용하고 싶을 때 시스템 콜을 통해 실행
시스템 콜이 발생하면 해당 커널 코드가 커널 모드에서 실행

</details>

<details><summary style="color:skyblue"> 메모리와 메모리 관리</summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/%EB%A9%94%EB%AA%A8%EB%A6%AC%EC%99%80-%EB%A9%94%EB%AA%A8%EB%A6%AC-%EA%B4%80%EB%A6%AC)

🪄 간단한 설명

1. 메모리
- CPU는 그저 메모리에 올라와 있는 프로그램의 명령어들을 실행

2. 메모리 계층
- 레지스터 : CPU 안에 있는 작은 메모리
- 캐시 : L1, L2 캐시를 지칭한다.
- 주기억장치 : (= 메모리, RAM)
- 저장장치(HDD SDD) : (= 보조기억장치)

3. 캐시
캐시는 데이터를 미리 복사해 놓는 임시 저장소이자 빠른 장치와 느린 장치에서 속도 차이에 따른 병목 현상을 줄이기 위한 메모리

4. 기억장치 관리
- 기억장치의 관리 전략의 개요
- 보조기억장치의 프로그램이나 데이터를 주기억장치에 적재시키는 시기(When), 적재 위치(Where) 등을 지정하여 한정된 주기억장치의 공간을 효율적으로 사용하기 위함
#반입(Fetch), 배치(Placement), 할당(Allocation), 교체(Replacemnet)
반배할교
</details>


# 서버관련
<details><summary style="color:skyblue"> 서버, 웹서버, WAS </summary>

[🔭 자세한 설명](https://velog.io/@prettylee620/CS-%EC%A7%80%EC%8B%9D-%EC%84%9C%EB%B2%84%EA%B4%80%EB%A0%A8)

<details><summary style="color:skyblue"> 서버</summary>
**1) 서버란..**
- 주된 정보의 제공이나, 작업을 수행하는 컴퓨터 시스템

### **2) 컴퓨터의 서버는 클라이언트에 서비스를 제공한다.**

웹브라우저 : 클라이언트
컴퓨터 : 서버

### **3) 서버의 처리는 클라이언트의 요청으로 시작된다.**

서버는 그 자체로  작동하는 것이 아니라, 불특정 다수의 컴퓨터에 대해 일방적으로 서비스를 제공하지 않음
클라이언트로부터 `요청(request)`을 받아서 처음으로 처리를 시작하고, 서비스를 `제공(응답, response)`한다.

1. 클라이언트는 서버에 무언가의 서비스를 요청한다.
2. 서버는 요청에 따라 맞춰 처리를 수행한다.
3. 서버는 처리 결과를 클라이언트로 반환
4. 클라이언트는 처리 결과를 받는다.

### **4) 웹서비스에 대입해보자**

**클라이언트** : 구글 크롬, 사파리와 같은 웹브라우저
**서버** : 웹사이트(의 구성 파일)이 있는 컴퓨터

5. 웹브라우저는 웹서버에 ㅇㅇ 사이트의 데이터를 주십시오라고 요청한다.
6. 웹서버는 ㅇㅇ 사이트의 파일을 찾는다.
7. 웹서버는 ㅇㅇ 사이트의 파일을 웹브라우저에 반환한다.
8. 웹브라우저는 ㅇㅇ사이트의 파일을 받아서 화면에 표시한다.
⇒ 이러한 시스템을 `클라이언트/서버 시스템`이라고 함   	
</details>

<details><summary style="color:skyblue"> 웹서버(Web Server)</summary>

**1. 웹서비스**
- 클라이언트 : 구글 크롬, 사파리와 같은 웹브라우저
- 서버 : 웹사이트(의 구성 파일)이 있는 컴퓨터

**2. 웹 서버란(WEB) = 아파치**
- 하드웨어와 소프트웨어 혹은 두 개가 같이 동작하는 것을 의미
- 말 그대로 작성된 html 페이지 등을 네트워크 망에 종속되지 않고, 웹서비스를 할 수 있도록 어플리케이션
- 브라우저에서 웹 서버에서 불려진 파일을 필요로 할 때, 브라우저는 HTTP를 통해 파일을 요청
- 요청이 올바른 웹 서버(하드웨어)에 도달 시, HTTP 서버(소프트웨어)는 요청된 문서를 HTTP를 이용해 보내줌
 </details>

<details><summary style="color:skyblue"> 웹 컨테이너(Web Container)</summary>

- `서블릿 컨테이너`라고도 함
- JSP + 서블릿을 실행시킬 수 있는 소프트웨어
- 웹 서버의 컴포넌트 중 하나로 자바 서블릿과 상호작용
- 서블릿의 생명주기를 관리하고, URL과 특정 서블릿을 맵핑하며 URL 요청이 올바른 접근 권한을 갖도록 보장
</details>

<details><summary style="color:skyblue"> WAS(Web Application Server) = tomcat</summary>

- 웹 서버 + 웹 컨테이너
- 인터넷 상에서 HTTP를 통해 사용자 컴퓨터나 장치에 애플리케이션을 수행해 주는 미들웨어(소프트웨어 엔진)
- 동적 서버 콘텐츠를 수행하는 것으로 일반적인 웹 서버와 구별되며, 주로 데이터베이스 서버와 같이 수행
- 웹 상에 사용하는 컴포넌트를 올려놓고 사용하게 되는 서버
</details>

<details><summary style="color:skyblue"> HTTPS vs HTTP </summary>

1. HTTP란?
- 웹 서비스를 위해 이용되는 프로토콜로 보안성이 안 좋음
- 암호화되지 않는 상태로 웹 볼 때 사용되는 프로토콜
- 인터넷에서 하이퍼텍스트(hypertext) 문서를 교환하기 위하여 사용되는 통신규약

2. HTTPS(HTTP Secure)란?
- 암호화된 상태로 웹을 볼 때 HTTP에 Secure을 뜻하는 s가 붙어 HTTPS

</details>

<details><summary style="color:skyblue"> 프로토콜 </summary>
1. 프로토콜이란?
- 통신 프로토콜 또는 통신 규약은 컴퓨터나 원거리 통신 장비 사이에서 메세지를 주고 받는 양식과 규칙의 체계, 통신 규약 및 약속
- 톰 마릴은 컴퓨터가 메세지를 전달하고, 메세지가 제대로 도착했는지 확인하며, 도착하지 않았을 경우 메세지를 재전송하는 일련의 방법을 기술적 은어로 프로토콜이라고 한다.
- 통신을 위해 프로토콜이 가져야 하는 일반적인 기능에는 데이터 처리 기능, 제어 기능, 관리적 기능

2. 프로토콜의 기본 요소
- `구문(Syntax)` : 전송하고자 하는 데이터의 형식(Format), 부호화(Coding), 신호 레벨(Singnal Level) 등을 규정
- `의미(Semantics)` : 두 기기간의 효율적이고 정확한 정보 전송을 위한 협조 사항과 오류 관리를 위한 제어 정보를 규정
- `시간(Timing)` : 두 기기 간의 통신 속도, 메세지의 순서 등을 규정

</details>
 
</details>

# 공부방법

<details><summary style="color:skyblue"> 컴퓨팅적 사고 방식</summary> 
	
[🔭 자세한 설명 :테오님 블로그](https://velog.io/@teo/computational-thinking)
</details>

# 강연 및 멘토링
<details><summary style="color:skyblue"> 센스있는 BE 개발자 되기 </summary> 
	
[🔭 자세한 강연 후기](https://velog.io/@prettylee620/%EC%A0%90%ED%95%8F-%EA%B0%95%EC%97%B0-%EC%84%BC%EC%8A%A4%EC%9E%88%EB%8A%94-BE-%EB%90%98%EA%B8%B0)


</details>

<details><summary style="color:skyblue"> 인프런 멘토 우연님 후기이자 방향성 - 초보개발자의 고민과 방안 </summary> 
	
[🔭 자세한 멘토 후기](https://velog.io/@prettylee620/%EC%9D%B8%ED%94%84%EB%9F%B0-%EB%A9%98%ED%86%A0-%EC%9A%B0%EC%97%B0%EB%8B%98-%ED%9B%84%EA%B8%B0%EC%9D%B4%EC%9E%90-%EB%B0%A9%ED%96%A5%EC%84%B1-%EC%B4%88%EB%B3%B4%EA%B0%9C%EB%B0%9C%EC%9E%90%EC%9D%98-%EA%B3%A0%EB%AF%BC%EB%93%A4)


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

- [라인 들어가신 분의 기술면접 공부법](https://velog.io/@rmswjdtn/%EC%B7%A8%EC%97%85-%EB%B0%B1%EC%97%94%EB%93%9C-%EC%8B%A0%EC%9E%85-14%EB%B2%88%EC%9D%98-%EB%A9%B4%EC%A0%91-%EA%B7%B8%EB%A6%AC%EA%B3%A0-%EC%B7%A8%EB%BD%80-4-%EA%B8%B0%EC%88%A0%EB%A9%B4%EC%A0%91)

- [널널한 개발자](https://www.youtube.com/watch?v=k1gyh9BlOT8&list=PLXvgR_grOs1BFH-TuqFsfHqbh-gpMbFoy)
: 네트워크 기초 개념 

- [김덕수님](https://www.youtube.com/watch?v=EdTtGv9w2sA&list=PLBrGAFAIyf5rby7QylRc6JxU5lzQ9c4tN)
  : 운영체제 기초 개념 유투브
