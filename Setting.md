# Kali-linux Setting

### <목차> ###

### 1)Download

  1. Oracle VM VirtualBox 설치
  2. kali linux 설치
  3. kali linux 압축 해제 후 VirtualBox Machine Definition(파란색) 실행


### 2)Setting

   1. 네트워크 -> 네트워크 연결을 'NAT' 형식으로 사용
   2. https://tryhackme.com/room/grootsecurity 접속
   3. 사용자 -> Access에서 Machines의 VPN Server를 AU-Regular-1으로 다운로드
   4. 다음의 명령어들을 입력


```
$ tmux                  // 선택
$ cd ~/Downloads        // 필수
$ ls -alh               // 필수
$ sudo openvpn ~~~.ovpn // 필수
```

  *참고*
  - tmux : 여러 터미널을 독립적으로 실행하기 위한 기능 
