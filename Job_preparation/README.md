# IT 취업을 위한 대비 질문 모음집

### 분야
#### OS(운영체제)
<details markdown="1">
<summary>프로세스와 쓰레드의 차이점</summary>

프로세스 : 간단히 말하면 실행중인 프로그램<br>
쓰레드 : 경량화 된 프로세스<br>
운영체제는 자원을 효율적으로 사용하려고 함. --> 쓰레드를 사용하면 프로세스에 비해서<br>
생성할 때 오버헤드도 적고 공유된 자원에 대해서도 오버헤드가 적음.<br>
그리고 쓰레드를 사용하면 병렬성을 높일 수 있음.<br>

</details>

<details markdown="1">
<summary>교착상태(데드 락 Deadlock)의 4가지 발생조건</summary>

1. 자원점유와 대기
  - 프로세스가 자원을 최소 하나는 보유해야함 / 다른 프로세스에 할당된 자원을 점유하기 위해선 대기하는 프로세스가 있어야함(대기해야한다는거)
2. 비선점
  - 이미 할당된 자원을 뺏을 수 없음(자원 약탈 불가능)
3. 순환적 자원 요구
  - 말 그대로임 대기 프로세스 집합이 순환 형태로 자원을 기다려야 한다는거임
4. 상호배제
  - 한번의 하나의 프로세스만 해당 자원을 사용하게 해주는거
해결법
- 예방
 - 발생 조건 4가지 중 하나라도 차단하는거
- 회피
 - 
- 탐지/회복
</details>

#### Network(네트워크)

<details markdown="1">
<summary>TCP 와 UDP 차이점</summary>
<h3>TCP</h3>
1. 신뢰성과 순차적인 전달이 필요한 경우 사용<br>
      2. 송진자와 수진사 모두가 `소켓`이라고 부르는 것을 생성함<br>
      3. 멀티캐스팅이나 브로드 캐스팅을 지원안함<br>
      4. 사전설정 필요 O 
<h3>UDP</h3>
1. 비연결형 프로토콜<br>
      2. 손상된 세그먼트의 수신에 대한 재전송X<br>
      3. 사전설정 필요 X <br>
</details>
