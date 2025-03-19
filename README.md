# 📌 AI 기반 일기 분석 서비스

## 🛠 프로젝트 개요
AI를 활용하여 사용자의 일기를 분석하고, 감정을 파악하여 맞춤형 도움을 제공하는 서비스입니다.

## 🚀 주요 기능
- 📝 **일기 작성 및 저장**
- 🤖 **OpenAI API를 이용한 감정 분석**
- 📊 **감정 및 키워드 분석 결과 제공**
- 💡 **맞춤형 도움 및 추천 기능**
- 🔒 **JWT 기반 사용자 인증 시스템**
- 📈 **월간 감정 변화 리포트 제공**
- 🌎 **AWS 배포 (추후 계획)**

## 🏗 기술 스택
### 💻 Backend (Spring Boot + Hibernate)
- Java 17
- Spring Boot 3.x
- Spring Data JPA (Hibernate)
- MySQL
- JWT (Spring Security)
- OpenAI API

### 🖥 Frontend (React)
- React (Vite)
- React Router
- Recoil or Redux
- Axios
- Chart.js (데이터 시각화)

### 🔧 DevOps & 환경설정
- Docker & Docker Compose
- GitHub Actions (CI/CD 예정)
- AWS EC2, RDS (추후 배포 예정)

## 🔥 프로젝트 실행 방법

### 🛠 백엔드 실행 (Spring Boot)
```bash
cd backend
./gradlew bootRun
