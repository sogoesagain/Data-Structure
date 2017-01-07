# 자료구조 (Data Structure)

## 자료구조란?

 자료구조란 데이터를 표현하고 저장하는 방법이다.

> 선형구조: 리스트, 스택, 큐
>
> 비선형구조: 트리, 그래프
>
> 파일구조: 순차파일, 색인파일, 직접파일
>
> 단순구조: 정수, 실수, 문자, 문자열

### 자료구조와 알고리즘

 알고리즘은 자료구조를 통해 저장된 데이터를 대상으로 어떤 문제의 해결 방법이다. 어떤 자료구조를 택하느냐에 따라 문제 해결을 위한 효율적인 접근이 달라지므로 알고리즘은 자료구조에 의존적이다.



## 알고리즘의 성능분석 방법

### 시간 복잡도(Time Complexity)

 알고리즘 수행시간을 분석

### 공간 복잡도(Space Complexity)

 알고리즘의 메모리 사용량을 분석

 문제 해결을 위한 최적의 솔루션을 찾기 위해서는 자료구조와 알고리즘을 평가할 수 있어야한다. 일반적으로 알고리즘을 평가할 때 공간 복잡도보다는 시간 복잡도에 초점을 둔다. 공간 복잡도는 특정 알고리즘에 대한 상대적인 우월성을 입증하는 경우에 사용되기도 한다. 무조건적으로 연산 속도가 빠른 알고리즘을 선택하는 것이 아니라 자료의 갯수, 구현의 난이도와 같이 문제 해결 상황에 맞는 알고리즘을 선택해야한다.

### 시간 복잡도 분석 방법

1. 처리해야 할 데이터의 수 n에 대한 연산횟수의 함수 T(n)을 구성한다. (핵심이 되는 연산에 대하여, 또 worst case에 대하여)
2. T(n)을 빅-오 표기법(Big-Oh Notation)으로 표현한다.

### 빅-오 표기법

 데이터 수의 증가에 따른 연산횟수 증가율의 상한선을 표현한 것. (수학적 정의 참고)

**대표적인 빅-오**

> O(1): 상수형 빅-오. 연산횟수가 고정인 유형의 알고리즘
>
> O(logn): 로그형 빅-오. 데이터 수의 증가율에 비해 연산횟수의 증가율이 훨씬 낮은 알고리즘
>
> O(n): 선형 빅-오. 데이터 수와 연산횟수가 비례
>
> O(nlogn): 선형로그형 빅-오.
>
> O(n^2): 중첩된 반복문에서 발생.
>
> O(n^3): 삼중으로 중첩된 반복문에서 발생.
>
> O(2^n): 지수형 빅-오. 사용하기에 무리가 있는 알고리즘.



# 참고문헌

1. 윤성우(2012). 윤성우의 열혈 자료구조