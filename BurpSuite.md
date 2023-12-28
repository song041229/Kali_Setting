# BurpSuite Setting

### 1. BurpSuite ###
  1) BurpSuite 실행
  2) Proxy -> Proxy settings -> Proxy listeners에서 Interface (ex. 127.0.0.1:8080) 확인

### 2. FoxyProxy ###
   1)FoxyProxy Standard 확장 : 8.x 버전은 호환성 문제 존재, 7.5.1 버전으로 사용
    -[FireFox Browser](https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/) : 추천
    -[Chrome Browser](https://chromewebstore.google.com/detail/foxyproxy/gcknhkkoolaabfmlnjonogaaifnjlfnp?hl=ko&pli=1)
       
   2)Open application menu -> Add-ons and themes -> FoxyProxy Standard의 Details -> Run in Private Windows 항목 : Allow로 변경
   
   3)FoxyProxy Options -> Add -> 'Title or Description (optional)' & 'Proxy IP address or DNS name' & 'Port' 입력  
     (ex. Title or Description (optional) : Burp  |  Proxy IP address or DNS name : 127.0.0.1  |  Port : 8080)
      
   4)FoxyProxy에서 'Use Enabled Proxies By Patterns and Order' 에서 'Burp'로 변경
   
   5)'http://burp/' -> CA Certificate 클릭 -> 다운로드한 'cacert.der' 파일을

   6)
