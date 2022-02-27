# 개인 프로젝트들

## 1. melon2youtube

### 프로젝트 목표 
멜론 플레이리스트를 읽어와 유투브 플레이리스트로 만들어주기. 
파이썬 + 셀레니움 으로 만들었으며, 타임아웃 예외처리 전이지만 돌아가긴 함. 

### 사용 기술 
Python 3  
Selenium framework

### 실행 방법
playlist_final = getMelon('플레이리스트 주소')
toYtube('구글 아이디' ,'구글 아이디 비밀번호' ,playlist_final)

### 주의 사항
구글 로그인 시 봇으로 로그인 탐지되어 막히는 현상.
=> Oauth 인증으로 우회도 안됨.
=> 플레이 리스트용 신규 계정 하나 생성해 실행하면 정상 실행됩니다.   

## 2. equipmentBySpring

### 프로젝트 목표
엑셀로 구현한 회사 재고 자산 관리 시스템을 spring framework + Java 로 웹으로 옮기기 
사내 장비 지급 현황, 수주 관리, 재고 자산을 관리하기 쉽도록 함.

### 사용 기술
- VBA
- Spring framework 
- Java 11 

