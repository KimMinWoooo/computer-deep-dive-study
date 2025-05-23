## 이 작은 장난감을 CPU라고 부른다

트랜지스터는 전류를 흐르게 하느냐/아니냐를 제어한다.

![캡쳐](https://velog.velcdn.com/images/ejay29/post/fe0cac38-94df-4124-a7a6-a52023ea63ac/image.jpeg)

논리곱, 논리합, 논리부정 조합으로 어떤 논리 함수도 구현할 수 있다.
트랜지스터 조합으로 이진수 덧셈을 수항하는 가산기(adder)를 만들 수 있다.
- CPU에는 덧셈 말고도 다른 산술 연살도 설계할 수 있는 모듈이 있다.
    - ALU(Arithmetic Logic Unit)
 
</br>

연산 말고도 회로는 기억을 할 수 있어야 한다.
부정 논리곱 게이트 두 개를 조합해서 기억장치를 만들 수 있다.

- 레지스터
    - 비트를 기억하기 위해 회로를 조합
 
</br>

- 명령어는 연산 코드와 오퍼랜드로 구성
    - 명령코드(operation code) : 수행할 연산 정보
    - 오퍼랜드(operand) : 연산에 사용할 데이터 또는 그 데이터의 주소값
 
- 16비트 주소
    - 표현 가능한 주소 수: 2¹⁶ = 65,536개
    - 64KB 메모리 접근 가능
 
- 32비트 주소
    - 표현 가능한 주소 수: 2³² = 4,294,967,296개
    - 4GB 메모리 접근 가능
 
</br>

CPU 클락 = **1초에 몇 번 명령어를 처리할 수 있는지**

- 클락 주기 (Clock Cycle)
    - CPU가 한 번의 기본 작업을 수행하는 데 걸리는 시간
    - 예: 데이터를 메모리에서 읽거나, 레지스터에 저장하거나, 연산 수행 등

- 클락 속도 (Clock Speed)
    - 단위: Hz (헤르츠)
    - 1Hz = 1초에 1번
    - 보통은 GHz(기가헤르츠) 단위로 표현

```
3.5GHz = 1초에 35억번 클락이 발생
= 이론적으로 CPU가 1초에 35억 번 연산 가능
```


- 계산할 수 있는 산술 논리 장치
- 정보를 저장할 수 있는 레지스터
- 작업을 함께하도록 제어해주는 클럭 신호
    - 이 모든 것을 한데 묶어서 중앙처리장치를 만듦
    - CPU 또는 프로세서라고 부름
 

