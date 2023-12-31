# BurpSuite Setting

## 1. BurpSuite ##
  1) BurpSuite 실행
  2) Proxy -> Proxy settings -> Proxy listeners에서 Interface (ex. 127.0.0.1:8080) 확인

## 2. FoxyProxy ##
   1) FoxyProxy Standard 확장 : 8. 버전은 호환성 문제 존재, 7.5.1 버전으로 사용 ( [FireFox Browser](https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/) | [Chrome Browser](https://chromewebstore.google.com/detail/foxyproxy/gcknhkkoolaabfmlnjonogaaifnjlfnp?hl=ko&pli=1) )
   2) Open application menu -> Add-ons and themes -> Details -> Run in Private Windows 항목 : Allow로 변경
   3) FoxyProxy Options -> Add -> 'Title or Description (optional)' & 'Proxy IP address or DNS name' & 'Port' 입력
  (ex. Title or Description (optional) : Burp  |  Proxy IP address or DNS name : 127.0.0.1  |  Port : 8080)
  4) FoxyProxy에서 'Use Enabled Proxies By Patterns and Order' 에서 'Burp'로 변경
  5) 'http://burp/' -> CA Certificate 클릭 ('cacert.der' 파일 자동 다운로드) 

## 3. FireFox Browser setting ##
  1) Open application menu -> Settings -> Privacy & Security 선택
  2) Certificates -> View Certificates -> Import 후 다운받았던 'cacaer.der' 파일 선택 -> OK

## 4. BurpSuite ##
  1) Proxy -> Intercept -> 'Intercept is off'를 'Intercept is on'으로 바꾸기 (제대로 트래픽을 intercept하고 있는지 확인)
  2) 'Learn more' 클릭 -> 정보 확인 가능 (Forward : 서버에 요청하기)
  3) Target -> Site map -> 원하는 URL 우클릭 -> Add to scope : 목표 트래픽 설정
  4) Filter -> 'Show only in-scope items' 선택 (Target, Proxy 둘 다) 
