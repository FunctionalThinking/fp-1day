(Korean)

함수형 프로그래밍 하루 과정
==========

Functional Thinking 커뮤니티에서 함수형 프로그래밍을 익힐 수 있는 하루짜리 입문 과정을 만들어보려고 합니다. 
Java 개발자, C 개발자들에게 직접적인 도움이 될 수 있도록 '사고의 도구'로서의 함수형 프로그래밍을 소개할 수 있으면 좋겠습니다.


# 함수형 프로그래밍 소개 자료 30분 짜리

대상: 함수형 프로그래밍을 처음 접하는 사람이나 개념 정도만 알고 있는 사람

목적: 함수형 프로그래밍의 중요 특성과 가치를 이해할 수 있도록 한다.

시간: 30분 이내.

## 이야기 구조
bottom-up language와 top-down language를 대비시킨다. 그 후 수학적 표현을 어떻게 프로그래밍으로 바꿀 수 있을까? 질문을 던진다.
그리고 binding과 reduction얘기를 한다.

**Bottom-up programming language**: 처음에는 기계를 위한 이진코드(기계어)가 있었다. 이를 사람이 이해하기 쉽게 만든 것이 Assembly였다. Assembly에 약간의 추상화를 더한 것이 C programming언어이다. C언어의 요소 중에 Assembly와 1:1대응 관계에 있는 것들이 꽤 있다. 

**Top-down programming language**: 문제를 풀기 위한 수학식이 있었다. 사람이 만든 이 수학식을 프로그래밍 언어로 표현하고 싶었다. 그래야 기계(컴퓨터)에서 돌릴 수 있으니까. 따라서 최대한 수학식을 자연스럽게 표현할 수 있는 프로그래밍 언어를 만들었다.

**Function**: Functional Programming에서 function은 수학에서 말하는 그 function과 같다. 함수는 어떤 특징을 가지는가? 함수는 동일한 입력에 대해서는 동일한 결과를 내놓는다. 아무리 여러 번 함수를 호출해도 같은 입력을 준다면 언제나 같은 결과를 얻을 수 있다. 이를 **referential transparency**라고 한다. 함수형 프로그래밍에는 **"상태(state)가 없다"**고 하는 것이 이러한 이유 때문이다. 이는 또한 **side effect free**와 관련이 있다. 만약 함수의 호출이 프로그램의 상태에 영향을 받는다면 동일한 입력에 대해 언제나 같은 결과를 얻는다고 보장 할 수 없다. 함수형 프로그래밍은 함수들의 조합으로 프로그래밍을 구성하기에 입력값이 같다면 언제나 같은 결과를 얻을 수 있다.


**Advantage over Imperative Programming**: 그래서 함수형 프로그래밍의 장점은 무엇인가?


(아래 내용은 30분 소개 자료에는 부적합)

**Applicative Programming**: functional programming을 뜻하는 비슷한 말로는 applicative programming이 있는데, 해당 프로그래밍 방법의 근본 구조가 application of a function to its argument라는 뜻에서 applicative programming이라고 부른다. 즉, 어떤 함수 f가 있을 때 이 함수 f에 인자 x를 적용하는 것이 해당 프로그래밍 방법의 근본 구조라는 뜻이다.


**Higher Order Function**: "고차함수", "높은 차원의 함수"라는 뜻의 말로 다른 함수를 인자로 받아 해당 함수에 대해 동작하는 함수를 뜻한다. "고차 함수"가 있다면 당연히 저차원 함수, 즉 1차원 함수도 있을 것이라고 생각할 것이다. 1차원 함수, 즉 first order function이란 수학식의 일반적인 연산자(+,-,x,/ 등등)를 뜻한다. first order function은 자료에 대해 동작하는 함수이다. 보통 이러한 first order function을 operator라고 부르기 때문에 그와 구분하기 위해 higher order function을 functionals라고 부른다. 즉, functional programming이란 이러한 functional들을 광범위하게 적용하는 형태로 프로그램을 구성하는 것을 말하는 것이다. higher order function의 대표적인 것으로 map이 있다. 

**Assignment vs. Binding**: 

**Free variable vs. Bound variable**:

**Closure**:


