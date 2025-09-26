# 🐝 MarketBEE  
소상공인을 위한 AI 기반 카드뉴스 생성 & 스마트 리포트 플랫폼  
<br>
> **배포 주소**: [http://marketbee.site](http://marketbee.site)

<br>
<br>

## 📖 프로젝트 소개
MarketBEE는 소상공인의 **폐업률 감소와 매출 증대**를 목표로 하는 AI 플랫폼입니다.  
홍보와 운영 전략에서 어려움을 겪는 자영업자들을 위해, **AI 카드뉴스 생성**, **스마트 리포트**, **맞춤형 마케팅 제안** 기능을 제공하여 사장님들이 **본업에 더 집중**할 수 있도록 돕습니다.  
<br>
<br>

## ✨ 주요 기능

- 🎨 **AI 카드뉴스 생성**  
  - GPT가 홍보 문구 자동 생성 + 이미지 API로 배경 이미지 생성  
  - 프론트에서 텍스트 합성 → AWS S3에 저장 & 마이페이지에서 열람 가능  

- 📊 **AI 스마트 리포트**  
  - 카카오맵 리뷰 분석 (핵심 키워드, 평균 평점)  
  - 매출 데이터 기반 시각화 (매출 추이, 메뉴별 판매 순위 등)  
  - 리뷰+매출 데이터를 종합해 **실질적 개선 팁 제공**  

- 🚀 **맞춤형 마케팅 제안**  
  - 매출 데이터를 기반으로 매장의 강·약점 분석  
  - 즉시 실행 가능한 **마케팅 이벤트** 자동 제안  

- 🤝 **제휴 관리 (B2B 기능)**  
  - 카카오맵 기반 주변 업장과 제휴 관계 맺기 및 관리  

- 📸 **사진 촬영 가이드**  
  - 업로드한 사진을 AI가 분석해 구도·조명·채도 개선 팁 제공  
<br>
<br>

## ⚙️ 기술 스택

**Backend**  
- Java 21, Spring Boot  
- MariaDB (AWS RDS), Redis  
- AWS EC2, AWS S3, Nginx  
- OpenAI GPT API  
- Python (크롤링, venv)  

**Frontend**  
- React, JavaScript, HTML  
- React Router, Zustand, Axios  
- React Calendar, React Canvas, React Chart  
- Module CSS  
- VSC, GitHub, Figma, npm   

<br>
<br>

## ⚒️ 서비스 아키텍쳐
<img width="4262" height="2590" alt="image" src="https://github.com/user-attachments/assets/72fdb6d1-3684-4f06-a921-91b83cfdb5ba" />

<br>
<br>

## 🖼️ 서비스 화면
실제 서비스에서 사용되는 주요 화면입니다.

### 1. 웰컴페이지 화면
<img width="1453" height="699" alt="image" src="https://github.com/user-attachments/assets/79a11ad9-a4a0-468e-8bc6-4269a3462c4d" />
<img width="1453" height="358" alt="image" src="https://github.com/user-attachments/assets/0f38b3b8-76bf-4e04-923a-ef580c9433f5" />
<img width="1453" height="563" alt="image" src="https://github.com/user-attachments/assets/eb4b40ed-960b-4cec-9174-d301d1e7d602" />
<img width="1451" height="638" alt="image" src="https://github.com/user-attachments/assets/816df15f-9762-4961-b1be-e0e83b83d7d6" />
<img width="1453" height="570" alt="image" src="https://github.com/user-attachments/assets/a990ebdf-5712-419f-81b2-265f39e2fe8c" />
<img width="1453" height="701" alt="image" src="https://github.com/user-attachments/assets/65ecf372-e198-4d5b-9219-611686133654" />

### 2. 업장 등록 화면
<img width="921" height="688" alt="image" src="https://github.com/user-attachments/assets/50d9aab8-5a63-435f-97a8-7b5061b10c9a" />

### 3. 메인페이지 화면
<img width="1453" height="660" alt="image" src="https://github.com/user-attachments/assets/b90e99ff-7e5b-4e3f-b907-a7e85f6c69e5" />

### 4. 카드뉴스 생성 화면
<img width="1000" height="654" alt="image" src="https://github.com/user-attachments/assets/c3861f98-ece8-401c-95d4-06df69271b50" />
<img width="1000" height="655" alt="image" src="https://github.com/user-attachments/assets/a088c073-fc93-47eb-be17-7dc631be96a4" />
<img width="1020" height="597" alt="image" src="https://github.com/user-attachments/assets/77be9cde-a358-45af-b1e1-0f399aee559d" />
<img width="1058" height="692" alt="image" src="https://github.com/user-attachments/assets/0e0c5466-2d00-4e5a-9537-45fa6a8791cb" />

### 5. 사진 촬영 가이드 화면
<img width="1453" height="682" alt="image" src="https://github.com/user-attachments/assets/a6c24df3-bfa0-4cee-979e-1a00f9a15990" />
<img width="1453" height="686" alt="image" src="https://github.com/user-attachments/assets/e15dc791-3680-4e85-a2af-636f5a06a87b" />

### 6. 스마트 리포트 & 마케팅 분석 화면
<img width="1247" height="686" alt="image" src="https://github.com/user-attachments/assets/749a7767-ed3d-44ea-a9f7-33d348edec40" />
<img width="1298" height="549" alt="image" src="https://github.com/user-attachments/assets/3cd2609f-9116-47c4-9465-2d657b98e375" />
<img width="1245" height="398" alt="image" src="https://github.com/user-attachments/assets/2c773fe3-b00f-4397-85f9-4014399f061f" />
<img width="1459" height="687" alt="image" src="https://github.com/user-attachments/assets/6977e404-2cd0-4c68-9bda-5b5ac5397896" />

<br>
<br>

## 👥 팀원 구성 및 역할

| 이름   | 직무         | 역할 |
|--------|-------------|------|
| 🙇‍♂️ 우승연 | 팀장 / 백엔드 | - 월컴페이지, 마이페이지, 카드뉴스 API 개발 <br> - RDS 설계 및 Redis 기반 무료 이용 횟수 관리 <br> - AWS EC2 + Nginx 배포 및 GitHub Actions CI/CD 구축 |
| 조은진 | 백엔드       | - 스마트리포트, 마케팅 분석 API 개발 <br> - 매출/리뷰 분석 모듈 구현 |
| 유재원 | 백엔드       | - 사진 촬영 가이드 API 개발 <br> - 소상공인 인터뷰 및 사용자 요구사항 조사 |
| 한종민 | 프론트엔드   | - React 기반 웰컴페이지/카드뉴스/사진촬영가이드/지도제휴 개발 <br> - Axios 연동 및 상태 관리 <br> - 프론트엔드 아키텍처 전반 구현 |
| 신상민 | 프론트엔드   | - React 기반 마이페이지/스마트리포트/마케팅분석 개발 <br> - 캘린더 뷰 및 API 연동 |
| 이채영 | 디자인       | - 서비스 UI/UX 디자인 <br> - 피그마 와이어프레임 제작 |


<br>
<br>
