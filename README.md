# Springboot Game Web page Project
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FSeJonJ%2FSpring-WebSocket-Chatting&count_bg=%233310C8&title_bg=%2316C86B&icon=&icon_color=%23E7E7E7&title=HITS&edge_flat=true)](https://hits.seeyoufarm.com)

## 0. Spring Boot 와 React 을 활용한 게임 웹사이트 프로젝트
- SpringBoot 기반 웹 사이트 개발 프로젝트를 진행

## 프로젝트 선정 배경
<img src="https://github.com/StarsinLiver/StarsinLiver.github.io/assets/141594965/68c641df-4d3c-4df5-be3b-4c5f4af59d74" width="500"/>
<img src="https://github.com/StarsinLiver/StarsinLiver.github.io/assets/141594965/94bb3268-9a62-4242-b1c9-24d7c36cefd9" width="500" />

### 브랜치별 설명
각자 맡은 역할에 따라 브랜치를 생성
- main    : 기본 프로젝트
- Junhee  : 상세조회 , 리뷰 , 태그별 게임 컬렉션
- junyeok : 결제 , News(뉴스) , About , 유저페이지 
- sanghwa : 게임 컬렉션, 메인페이지, 관리자페이지(front)
- sanha   : 로그인 및 회원가입 기능 , 메인페이지 , 관리자 페이지(backend)

## 1. 사용기술 - FRONT
- React
- JQuery
- BootStrap
- Redux
- steam API
- toss payments API

## 1-2. 사용기술 - Backend
- Java 11
- Spring Boot MVC
- Gradle
- kakao openAPI
- google openAPI
- Oracle DATABASE
- AWS EC2
- GABIA (도메인)

![1706859882414-4c2a9d00-e4c7-47df-ab00-e5ebc180871a_11](https://github.com/StarsinLiver/StarsinLiver.github.io/assets/141594965/0cfc01bb-44c2-4936-a440-73715183f4f0)

## 2. ERD 
![1706859882414-4c2a9d00-e4c7-47df-ab00-e5ebc180871a_14](https://github.com/StarsinLiver/StarsinLiver.github.io/assets/141594965/8abc2928-88fd-4ac5-8413-62df7b9cc142)

## 3. 구현 기능
1) 로그인/회원가입
   - GOOGLE , KAKAO OPEN API를 활용한 간편로그인
   - 비밀번호 찾기 기능
   - 자체 회원가입 기능
2) 메인페이지
   - 추천게임 목록 
   - 금주의 할인 게임 (할인율 적용시 나타나는 페이지)
   - 액션 , 무료 게임 탭 기능
   - 카테고리별 순위 
3) 전체조회
   - 검색 기능
     - 게임 이름 검색창
     - 태그별 선택창
     - 가격별 선택창
     - 리뷰 평가 선택창
4) 상세조회
   - 게임 설명
   - 게임 carousel 형식 이미지 , 동영상
   - 장바구니 기능
   - 태그 기능
   - 최근 소식
   - 컴퓨터 사양
   - 해당 게임 공유 기능
   - 리뷰 기능
5) 장바구니
   - 장바구니 담기 , 삭제
6) 결제 기능
   - toss payment API 를 활용
   - mail JS 를 활용한 결제 내역 메일 전송
   - 포인트 활용 기능
7) 마이 페이지
   - 구매한 게임 목록
   - 회원 정보 수정
     - 이름 , 설명 , 패스워드
   - 구매 내역 목록 확인
   - QNA 작성 / 수정 / 내역 확인
   - 환불 요청 / 수정 / 내역 확인
8) 뉴스
9) 관리자 페이지
   - steam API
     - 게임 검색 기능
     - 게임 상세 조회 기능
   - 상품
     - 등록 , 수정 , 삭제
   - 환불
     - 일반 유저가 환불 요청시 환불 목록 확인
     - 환불을 요청한 유저의 정보 , 게임정보 내역
     - 환불 승인 , 거절
   - QNA
     - 일반 유저가 작성한 QNA 목록 확인
     - 글 작성 , 수정 기능

## 7. 구동 화면

![](info/chattingFileUpload.gif)  

### 화상 채팅 화면
![ChatForYou.gif](info%2FChatForYou.gif)  
  
### Grafana 성능 모니터링 && Access 모니터링  
![monitoring.png](info%2Fmonitoring.png)

### DataChannel file Up/Download
![chatforyou_fileupdown.gif](info%2Fchatforyou_fileupdown.gif)

