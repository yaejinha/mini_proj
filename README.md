# Personal Project

## 1. melon2youtube

### Project goal
Read Melon's playlist ( * Melon: Korean music streaming service) and convert it into Youtube playlist

### Used technology
#### By Selenum, it grabs dom elements of website & conducts a scenario like an UI test. 
☑️Python 3  
☑️Selenium framework

### How to use
playlist_final = getMelon('playlist URI')
toYtube('Google id' ,'Google pwd' ,playlist_final)

###Before you use it 
Google prevents automated bot to log into Youtube 
=> Oauth detour doesn't work. 
=> make a new account and run it. It will work. 
I will fix it later. 

---
# 개인 프로젝트들

### 프로젝트 목표 
멜론 플레이리스트를 읽어와 유투브 플레이리스트로 만들어주기. 
파이썬 + 셀레니움 으로 만들었으며, 타임아웃 예외처리 전이지만 돌아가긴 함. 

### 사용 기술 
### 셀레니움을 이용해 UI 테스트 하듯이 dom element 조작으로 수행
☑️Python 3  
☑️Selenium framework

### 실행 방법
playlist_final = getMelon('플레이리스트 주소')
toYtube('구글 아이디' ,'구글 아이디 비밀번호' ,playlist_final)

### 주의 사항
구글 로그인 시 봇으로 로그인 탐지되어 막히는 현상.
=> Oauth 인증으로 우회도 안됨.
=> 플레이 리스트용 신규 계정 하나 생성해 실행하면 정상 실행됩니다.   
