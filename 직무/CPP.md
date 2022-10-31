# C++




<details>
<summary><strong>Constructor와 Destructor에 대해 설명하라.</strong></summary>
  <hr>

  **생성자**: 객체가 생성될 때 실행되는 함수, 객체의 초기화가 목적

  **소멸자**: 객체의 사용이 끝나고 메모리에 반환될때 실행되는 함수

  <hr>
</details>




<details>
<summary><strong>C++에서 Default Constructor는 무엇을 의미하는가?</strong></summary>
<hr>

   클래스에는 생성자가 반드시 있어야 한다.

   사용자가 생성자를 따로 생성하지 않으면 컴파일러가 기본 생성자를 자동으로 생성해준다.

<hr>
</details>




<details>
   <summary><strong>C++에서 <code>Virtual function</code>은 왜 존재하는가?</strong></summary>
   <hr>

   오버라이딩을 기대하는 함수에 쓴다.

   virtual을 쓰면 런타임에 함수가 매핑이 되는 동적바인딩이 수행된다.
  C++에서 자식 클래스에서 재정의(오버라이딩)할 것으로 기대하는 멤버 함수를 의미함

멤버 함수 앞에 virtual 키워드를 사용하여 선언함 → 실행시간에 함수의 다형성을 구현할 때 사용



   <hr>
</details>




<details>
  <summary><code>\n</code>과 <code>endl</code>의 차이는 무엇인가?</summary>
  <hr>
  \n과 endl 모두 출력할 때 개행(줄 띄움)을 위해 사용한다.
둘의 차이는 endl은 출력 버퍼를 비워주는 과정(flush)이 들어가 있어서 \n보다 느리다.
버퍼는 입출력을 프로그램에 바로 전달하지 않고 임시 메모리 공간에 저장한 후 한번에 전송하는 역할을 한다. 
버퍼를 즉시 비우고 싶다면 endl을 그렇지 않다면 \n을 사용한다.
하지만 구현체(ex printf, println, cout 등등의 출력 함수)에 따라서 "\n"도 버퍼를 비우도록 처리하는 경우도 있다고 한다.
  <hr>
</details>




<details>
   <summary><strong><code>malloc</code>과 <code>new</code>의 차이는 무엇인가?</strong></summary>
   <hr>

   malloc은 함수이다. 함수 내에서 메모리를 할당한다.

   new는 연산자이다. 생성자를 호출하면서 메모리를 할당한다.

   <hr>
</details>




<details>
   <summary><strong>struct와 class의 차이는 무엇인가?</strong></summary>
   <hr>

   둘 다 데이터를 담는 그릇이다.

   struct : 기본 접근 제어자 public

   class : 기본 접근 제어자 private

   <hr>
</details>
