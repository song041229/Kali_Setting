# tmux

### 1. Theory ###
  - 여러 터미널을 독립적인 환경에서 실행
  - 프로그램 분리에 유용

### 2. Download ###
  ```
  sudo apt-get install tmux
  ```
  - 참고 : 일반적으로 내장되어 있음

### 3. Command ###

1. Session
  ```
  # 새로운 세션 생성 (default : 숫자)
  $ tmux

  # 이름을 지정하여 세션 생성
  $ tmux new -s <name>


  # 현재 세션 list
  $ tumx ls

  # 특정 이름인 세션으로 돌아가기
  $ tumx a -t <name>
  ```

2. Window
  ```
  # 새로운 윈도우 생성
  $ ctrl+b, c

  # 현재 윈도우 닫기
  $ ctrl+d


  # 이전 윈도우로 이동
  $ ctrl+b -> p

  # 다음 윈도우로 이동
  $ ctrl+b -> n 

 
  ctrl+b -> , : 현재 윈도우 이름 바꾸기

  ctrl+b -> w : 현재 윈도우 목록 나열
  ```

3. Extra
  ```

  ```
