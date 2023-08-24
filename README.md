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

### 순차적 애플리케이션

1. `순차적`으로 실행되어야 하는 애플리케이션이라면.. 그래서 잘게 쪼개서 동시에 실행하기 매우 어려운 성격의 애플리케이션이라면 **스레드를 많이 쓰려고 해도 실제 사용할 수 있는 스레드 수는 제한이 생김**
2. 코어에서 실행되던 스레드가 다른 스레드로 바뀔 때마다,`context switching`을 하는데, 이런 스위칭 작업도 **CPU 코어에서 실행**되게 되는 작업
3. 즉, 코어에서 `스위칭 작업`을 처리하는 동안에는 **애플리케이션 코드가 실행되지 않음**
    1. `overhead` : 이때, 스위칭 작업을 위해 소비되는 **CPU time**은 애플리케이션과 직접적인 관련은 없지만 멀티스레딩으로 동작하기 위해 필요하기 때문에 간접 방식이라고 부름
4. 위의 지식을 바탕으로 CPU의 코어 수는 고정되어 있는데 스레드 수를 계속 늘리게 되면 한 코어에서 경합해야하는 스레드의 수는 더 늘어나기 때문에 **OVERHead**도 많아짐 ⇒ 한계

### CPU bound, I/O bound 관점

#### CPU bound 애플리케이션

1. cpu를 많이 쓰기 떄문에 코어 수와 비슷한 수준 이상으로 스레드 수를 늘려봤자 이점이 없다.
2. 오히려 각 코어에서 경합하는 스레드 수가 많아질 수

록히 context switching 때문에 overhead만 더 많아져서 성능에 안 좋은 영향

### I/O bound 애플리케이션

1. I/O 작업이 많기 때문에 CPU가 놀고 있는 시간이 많다.
2. 코어 수보다 두~세배 늘려주는 것이 overhead가 늘긴 해도 코어들을 좀 더 효율적으로 사용 가능하기에 성능 이점이 있음
3. 물론 너무 많이 늘리면 안좋음
	
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

- [라인 들어가신 분의 기술면접 공부법](https://velog.io/@rmswjdtn/%EC%B7%A8%EC%97%85-%EB%B0%B1%EC%97%94%EB%93%9C-%EC%8B%A0%EC%9E%85-14%EB%B2%88%EC%9D%98-%EB%A9%B4%EC%A0%91-%EA%B7%B8%EB%A6%AC%EA%B3%A0-%EC%B7%A8%EB%BD%80-4-%EA%B8%B0%EC%88%A0%EB%A9%B4%EC%A0%91)

- [널널한 개발자](https://www.youtube.com/watch?v=k1gyh9BlOT8&list=PLXvgR_grOs1BFH-TuqFsfHqbh-gpMbFoy)
: 네트워크 기초 개념 

- [김덕수님](https://www.youtube.com/watch?v=EdTtGv9w2sA&list=PLBrGAFAIyf5rby7QylRc6JxU5lzQ9c4tN)
  : 운영체제 기초 개념 유투브
