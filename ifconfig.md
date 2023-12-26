# ifconfig

### 1. Theory ###
  - 네트워크 인터페이스

### 2. Command ###

1. 네트워크 인터페이스

  ```
  # 모든 네트워크 인터페이스 성정
  $ ifconfig

  # 특정 네트워크 인터페이스 설정
  $ ifcongfig <name>


  # 네트워크 인터페이스 활성화
  $ sudo ifconfig <name> up

  # 네트워크 인터페이스 비활성화
  $ sudo ifconfig <name> down
  ```

2. 네트워크 인터페이스의 매개변수 설정

  ```
  # ip 주소 할당
  $ ifconfig <name> <ip>

  # 넷마스크 할당
  $ ifconfig <name> netmask <netmask>

  # 브로드캐스트 할당
  $ ifconfig <name> broadcast <broadcast>

  # MAC 주소 변경
  $ ifconfig <name> hw ether

  # MTU(패킷 제한 크기) 변경
  $ ifconfig <name> mtu


  # promiscuous 모드 활성화
  $ ifconfig <name> promisc

  # primiscuous 모드 비활성화
  $ ifconfig <name> -promisc
  ```

