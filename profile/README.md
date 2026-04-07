# ⚾ FullCount
> SK쉴더스 루키즈 5기 지능형 애플리케이션 개발자 양성과정 - 미니프로젝트2 5조

야구 팬을 위한 직관 커뮤니티와 안전한 티켓 양도 플랫폼입니다.

FullCount는 같은 팀을 응원하는 팬들이 경기 일정에 맞춰 직관 메이트와 크루를 모집하고, 실시간 채팅으로 소통하며, 개인 간 티켓 양도를 에스크로 형식으로 안전하게 진행할 수 있도록 돕는 서비스입니다. KBO 경기 일정과 경기 현황을 기반으로 오프라인 직관 경험을 온라인 커뮤니티와 연결합니다.

&nbsp;
## ✨ Main Feature
### 1. KBO 경기 정보 및 실시간 경기 조회
<img width="800" alt="image" src="https://github.com/user-attachments/assets/b20b91f3-1c1a-4f1a-a44d-3177ebf97409" />
<img width="800" alt="image" src="https://github.com/user-attachments/assets/a4f8490c-3a7d-4a2b-9559-30d5d5c810a7" />
<img width="800" alt="image" src="https://github.com/user-attachments/assets/f44685d0-7e7e-4969-a708-0dfb71b14b9f" />

- 당일 경기 및 라이브 경기 현황 조회, 실시간 라이브 채팅
- 경기 결과 기반 직관 기록 연결
- 날짜별 KBO 경기 일정 및 결과 조회
- 네이버 스포츠 API 및 KBO 데이터 연동 구조

&nbsp;
### 2. 회원 관리 및 팀 기반 서비스
<img width="800" alt="image" src="https://github.com/user-attachments/assets/5fa43941-2a73-484a-b7fc-c33f4d93a604" />
<img width="800" alt="image" src="https://github.com/user-attachments/assets/346a348b-65ff-4e70-9e71-58dd5015145d" />

- 이메일 기반 회원가입과 JWT 인증
- KBO 응원 팀 선택 및 팀 기반 사용자 경험
- 활동 이력에 따른 배지 등급 관리
- 직관 기록, 관람 결과, 인증 이미지, 메모 관리


&nbsp;
### 3. 직관 메이트 및 크루 모집
<img width="800" alt="image" src="https://github.com/user-attachments/assets/caa7a281-eebc-4065-800d-4dba9bb2b996" />
<img width="800" alt="image" src="https://github.com/user-attachments/assets/9fc5e1f0-83c1-41a9-ab1e-d439eb22c3e6" />
<img width="800" alt="image 2026-04-07 140322" src="https://github.com/user-attachments/assets/ef499b73-46dc-4ed7-9228-0732699d42cb" />


- 경기 일정, 경기장, 모집 인원, 좌석 정보 기반 모집 게시글 작성
- 직관 메이트와 크루 모집 게시글 조회, 수정, 삭제
- 참여 신청 및 승인 흐름
- 모집 확정 후 참여자 전용 그룹 채팅방 운영

&nbsp;
### 4. 티켓 양도 및 거래
<img width="800" alt="image" src="https://github.com/user-attachments/assets/6bb97012-44c6-451d-9990-97fee92362c9" />
<img width="800" alt="image" src="https://github.com/user-attachments/assets/b8862b28-273d-4a23-b1a9-455928ad840a" />
<img width="800" alt="image" src="https://github.com/user-attachments/assets/b3ead3fc-c229-4cbe-be73-d59cbcab09c7" />

- 티켓 양도 게시글 등록 및 조회
- 양도 요청 기반 1:1 채팅방 생성
- 거래 상태 관리
- 안전한 거래 흐름을 위한 에스크로 기반 결제 및 정산 정책
- 정가 초과 거래, 허위 정보, 비정상 거래 방지를 위한 운영 정책

&nbsp;
### 5. 실시간 채팅
<img width="800" alt="image" src="https://github.com/user-attachments/assets/56a4fab8-effd-448b-9f43-319d185d548a" />
<img width="800" alt="image" src="https://github.com/user-attachments/assets/e1b0315a-de97-4bcd-b6ee-824b38d330a5" />

- WebSocket, STOMP 기반 실시간 메시징
- 1:1 채팅과 그룹 채팅 지원
- 채팅방 참여자 관리
- 읽지 않은 메시지 상태 관리
- 라이브 응원 채팅 지원

&nbsp;
### 6. 관리자 기능
<img width="800" alt="image" src="https://github.com/user-attachments/assets/921ec13a-2831-47de-ba2c-30e9af31cdcd" />
<img width="800" alt="image" src="https://github.com/user-attachments/assets/a719e9bd-44a4-4313-9199-c3d94ed700b2" />

- 회원, 게시글, 거래 현황 모니터링
- 비정상 거래 및 운영 정책 위반 관리
- 회원 비활성화 및 관리자 권한 처리
- 관리자 대시보드 기반 통계 확인

&nbsp;
## 🔧 Tech Stack

### Backend

![Java](https://img.shields.io/badge/Java-17-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2.5-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-339933?style=for-the-badge&logo=spring&logoColor=white)
![Jsoup](https://img.shields.io/badge/Jsoup-2F6F3E?style=for-the-badge)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![STOMP](https://img.shields.io/badge/STOMP-4B5563?style=for-the-badge)
![SockJS](https://img.shields.io/badge/SockJS-4B5563?style=for-the-badge)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white)
![SpringDoc OpenAPI](https://img.shields.io/badge/SpringDoc%20OpenAPI-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS](https://img.shields.io/badge/Vanilla%20CSS-Mobile--First-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React Context API](https://img.shields.io/badge/React%20Context%20API-AuthContext-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)
![StompJS](https://img.shields.io/badge/StompJS-4B5563?style=for-the-badge)
![SockJS](https://img.shields.io/badge/SockJS-4B5563?style=for-the-badge)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### Database

![MySQL](https://img.shields.io/badge/MySQL-8.x-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![H2](https://img.shields.io/badge/H2-Database-1F6FEB?style=for-the-badge)

&nbsp;
## 🗂 Document
- [도메인 설계서](https://github.com/Rookies5-MiniPj2-Team5/.github/blob/main/1_%EB%8F%84%EB%A9%94%EC%9D%B8%20%EC%84%A4%EA%B3%84%EC%84%9C_5%EC%A1%B0.md)
- [Entity 설계서](https://github.com/Rookies5-MiniPj2-Team5/.github/blob/main/2_Entity%20%EC%84%A4%EA%B3%84%EC%84%9C_5%EC%A1%B0.md)
- [REST API 설계서](https://github.com/Rookies5-MiniPj2-Team5/.github/blob/main/3_REST%20API%20%EC%84%A4%EA%B3%84%EC%84%9C_5%EC%A1%B0.md)
- [UI 화면 설계서](https://github.com/Rookies5-MiniPj2-Team5/.github/blob/main/4_UI%20%ED%99%94%EB%A9%B4%20%EC%84%A4%EA%B3%84%EC%84%9C_5%EC%A1%B0.pdf)
- [React 컴포넌트와 Props/State 설계서](https://github.com/Rookies5-MiniPj2-Team5/.github/blob/main/5_React%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8%EC%99%80%20Props_State%20%EC%84%A4%EA%B3%84%EC%84%9C_5%EC%A1%B0.md)

&nbsp;
## 🔗 Repository

- [Backend Repository](https://github.com/Rookies5-MiniPj2-Team5/FullCount-BE)
- [Frontend Repository](https://github.com/Rookies5-MiniPj2-Team5/FullCount-FE)

&nbsp;
## 💻 Developers
| <a href="https://github.com/anjin0910-afk" target="_blank"><img width="120" height="120" src="https://github.com/anjin0910-afk.png" /></a> | <a href="https://github.com/Eojinn" target="_blank"><img width="120" height="120" src="https://github.com/Eojinn.png" /></a> | <a href="https://github.com/mmije0ng" target="_blank"><img width="120" height="120" src="https://github.com/mmije0ng.png" /></a> | <a href="https://github.com/siyeon04" target="_blank"><img width="120" height="120" src="https://github.com/siyeon04.png" /></a> | <a href="https://github.com/qwer9679" target="_blank"><img width="120" height="120" src="https://github.com/qwer9679.png" /></a> |
|:-------------:|:------:|:------:|:------:|:------:|
| [안진경(팀장)](https://github.com/anjin0910-afk) | [김어진](https://github.com/Eojinn) | [박미정](https://github.com/mmije0ng) | [이시연](https://github.com/siyeon04) | [이준호](https://github.com/qwer9679) |
