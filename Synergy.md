# Synergy 소개

## 1)개요
#### -서로 다른 운영체제의 2개의 PC를 키보드/마우스 한세트로 조작할 수 있는 소프트웨어
#### -현재 유료이나 과거 무료버전을 찾아 사용 가능


## 2)설치환경
#### - 윈도우10(Server) / 우분투18.04(Client)
    
## 3)Synergy 버전
#### - 윈도우 : synergy-v1.8.8-stable-Windows-x64.msi
#### - 우분투 : synergy-v1.8.8-stable-Linux-x86_64.deb

## 4)기능
#### - 클립보드 문자 copy&paste
#### - 토글키 활용(alt+p/o)하여 마치 alt+tab을 활용하듯이 서로 다른 pc로 전환
#### - FTP 트러블슈팅 실패

## 5)트러블슈팅


    synergy failed to connect secure socket
      
-상단 메뉴의 Edit > Setting > SSL관련 체크박스를 Client와 Server 동일하게 잡기
※무료버젼은 SSL지원 안하므로 Uncheck한다.

     
     
    synergy failed to connect to server incompatible client 1.5
      
- 두 pc의 synergy버전을 맞추고 해결하였다.
- synergy 재설치로 해결했다는 케이스도 있으니 참고할것

(https://symless.com/forums/topic/3582-failed-to-connect-to-server-incompatible-client-15/)



     
    Server refused client with our name [Client명]

- Server의 Configure에서 Client명 잡아줌

(https://symless.com/forums/topic/2550-server-refused-client-with-our-name/)
