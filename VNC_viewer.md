# VNC 뷰어

## 1)개요
#### -팀뷰어와 같은 원격프로그램

## 2)설치환경
#### 우분투18.04(server) / 안드로이드(client)
    
## 3)설치방법
#### - 모바일

> vnc viewer 다운로드

#### - 우분투  
##### 첫번째, 환경설정에서 스크린셰어링 허용
> 설정 -> sharing -> on -> ScreenSharing -> required password
##### 두번째, dconf-editor 설치 
`sudo apt install dconf-editor`
##### 세번째, dconf editor 실행하여 설정잡기
> /org/gnome/desktop/remote-access/ 경로에서 require-encryption 꺼주기


