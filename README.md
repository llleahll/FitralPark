# 🏋️‍♂️ FitralPark JSP 웹 프로젝트

> 개인 맞춤형 헬스케어 관리 JSP 기반 웹 애플리케이션  
> 식단, 운동, 헬스장 예약/관리 기능을 제공하며  
> 사용자 친화적인 UI와 실시간 데이터 연동으로 건강 관리 경험을 지원합니다.

---

## ✨ 프로젝트 개요
- **프로젝트 기간**: 2025.03.24 ~ 2025.04.04 (12일)  
- **팀 구성**: 6명  
- **담당 업무**:  
  - 메인페이지: 프론트 인덱스 (헤더/푸터/사이드바) 구현  
  - 식단관리: 프론트 + 백엔드 기능 구현

---

## 🔧 기술 스택 & 개발 환경
- **Frontend**: JSP, HTML5, CSS3, JavaScript, Ajax  
- **Backend**: Java (JDK 17), Servlet  
- **Database**: Oracle XE 18c, 공공 API 연동  
- **Version Control**: Git  
- **Tools & IDE**: Eclipse, IntelliJ IDEA, VS Code, SQL Developer  
- **OS**: Windows 11

---

## 📂 프로젝트 구조


## 🚀 주요 기능

FitralPark는 사용자 맞춤형 건강 관리 플랫폼으로, **마이페이지, 식단 관리, 운동 관리, 식품 영양 검색, 멘토 서비스, 커뮤니티, 헬스장 정보 제공** 등 다양한 기능을 제공합니다.  

### 1️⃣ 홈 (Main)
- 로그인/회원 인증 후 메인 기능 접근  
- 추천 식단, 운동 루틴, 헬스장 정보 표시  
- **⭐담당**: 메인페이지 프론트 인덱스 UI 구현  

### 2️⃣ 식단 관리
- 맞춤형 식단 추천 및 CRUD 기능  
- **⭐담당**: 프론트 + 백엔드 기능 구현  
- 실시간 데이터 반영 (Ajax 활용)  
- CSS/레이아웃 조정으로 테이블 깨짐 방지  
- 기록/비교/피드백 기능 포함

### 3️⃣ 커뮤니티
- Q&A, 정보 공유 및 피드백 기능  
- 친구 추천, 팔로우 기능  
- 사용자 간 경험 및 노하우 공유  

### 4️⃣ 식품/영양 성분 분석
- 식품 성분 및 영양 정보 검색  
- 식단 레시피 추천 및 비교 기능  
- 사용자 기록 기반 맞춤형 영양 피드백  

### 5️⃣ 운동 & 피트니스
- 운동 루틴 등록 및 기록 관리  
- 루틴별 기록 비교 및 통계 확인  
- 헬스장 정보 제공: 위치, 시설, 운영 시간  

### 6️⃣ 멘토 서비스
- 멘토 인증: 전문가 목록 확인, 게시물 인증 마크 표시  
- 온라인 PT: 식단 관리, 운동 계획 제공 및 결제 시스템  
- 전문가 상담 예약: 예약 관리 및 피드백 시스템 제공 

### 7️⃣ 마이페이지
- 개인 건강 기록 조회 (체중, 운동량, 식단 기록)  
- 목표 설정 및 진행 상황 확인  
- Todo-list, 일정 관리, 맞춤 알람 기능  

---

## 💻 실행 화면

### 🛍️ 메인 페이지

| 기능 | 화면 |
|------|------|
| 전체 메인 인덱스 | <img src="https://github.com/user-attachments/assets/d62caf1f-969e-4ed7-bd3f-b26f1928bb9e" width="800"> |
| 네비게이션바 상세 메뉴 | <img src="https://github.com/user-attachments/assets/0d2b153a-1d87-441f-a567-857b45227f49" width="800"> |
| 로그인 헤더 알림 | <img src="https://github.com/user-attachments/assets/b2c93eed-78d2-43de-9018-4ab97a8b7f02" width="800"> |
| 알람 수신 토글바 | <img src="https://github.com/user-attachments/assets/37f545ca-5fd1-404f-a5c5-2a12eaf57332" width="800"> |
| 풀 메뉴 | <img src="https://github.com/user-attachments/assets/5cfbb15d-c8c6-42d2-b163-f4fe13ee98d5" width="800"> |
| 사이드바 | <img src="https://github.com/user-attachments/assets/945fe2e4-9b5a-4819-8a8d-4a5b848e9e9a" width="90"> |

---

### 🥗 식단 캘린더 & 관리

| 기능 | 화면 |
|------|------|
| 식단 캘린더 (월별/주별 보기) | <img src="https://github.com/user-attachments/assets/1a348ab6-298f-4da6-b29a-da5cbef9a34a" width="800"> |
| 식단 캘린더 (식단 불러오기) | <img src="https://github.com/user-attachments/assets/2f7ea562-66b4-486c-90ca-38a59b397a6e" width="1000"> |
| 식단 생성 (신규 등록) | <img src="https://github.com/user-attachments/assets/079f7e5e-0a57-469d-adc3-a1a8baaf7a27" width="600"> |
| 식단 리스트 (등록된 식단 확인) | <img src="https://github.com/user-attachments/assets/76ca207d-7bd2-4ee1-b2c0-e2109163ad72" width="800"> |

---

### 📊 식단 분석

| 기능 | 화면 |
|------|------|
| 식단 분석 화면 (영양소 기반 분석 결과 제공) | <img src="https://github.com/user-attachments/assets/6a412776-f89e-4968-957e-153b096432a1" width="800"> |

---

## 📂 프로젝트 구조
```
fitralpark/
├── src/main/java/com.fitralpark/
│ ├── controller/          # Servlet 컨트롤러
│ ├── dao/                 # DB 접근 객체
│ ├── dto/                 # 데이터 전송 객체(DTO)
│ ├── service/             # 비즈니스 로직
│ └── FitralParkApplication.java
├── WebContent/
│ ├── css/                 # 스타일시트
│ ├── js/                  # JavaScript
│ ├── images/              # 이미지
│ ├── jsp/                 # JSP 페이지
│ └── WEB-INF/
│ └── web.xml              # 서블릿 설정
├── database/
│ └── fitralpark_DDL.sql   # 테이블 생성 스크립트
└── README.md
```
---

## 🚀 실행 방법

### 1️⃣ DB 세팅
- Oracle XE 18c 설치 후, 제공된 SQL 스크립트(`FitralPark_DDL.sql`) 실행
- 데이터베이스 및 테이블 생성 확인

### 2️⃣ 프로젝트 열기
- Eclipse 또는 IntelliJ IDEA에서 **Dynamic Web Project**로 프로젝트 임포트

### 3️⃣ 서버 설정
- Tomcat 9 이상 설치 및 프로젝트 연결
- `web.xml` 및 `context.xml`에서 DB 접속 정보 확인/수정

### 4️⃣ 환경 설정
- `db.properties`에서 DB 계정, 비밀번호, URL 확인 및 필요 시 수정

### 5️⃣ 서버 구동
- **Eclipse**: 프로젝트 우클릭 → Run As → Run on Server  
- **IntelliJ IDEA**: Tomcat 설정 후 Run 클릭

### 6️⃣ 접속 주소
- 사용자 페이지: `http://localhost:8090/FitralPark/`
---

