# tmux

### 1. Theory ###
  - 여러 터미널을 독립적인 환경에서 실행
  - 프로그램 분리에 유용

### 2. Download ###
  ```
  sudo apt-get install tmux
  ```
  #### - 참고 : 일반적으로 내장되어 있음

### 3. How to use ###

  ```
  tmux : 새로운 세션 시작
  tmux new -s {name} : {name} 이름으로 세션 시작
  tumx ls : 현재 세션 list
  tumx a -t {name} : {name}인 세션으로 돌아가기
  ```
