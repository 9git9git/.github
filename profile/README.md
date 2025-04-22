# 구깃 (9git) - 내 하루의 구깃

필요한 순간만 접어놓다, 내 하루의 구깃

## 📋 프로젝트 개요

구깃은 사용자의 하루를 더 효율적으로 관리할 수 있도록 도와주는 서비스입니다. 사용자의 일정과 메모를 관리하고, AI를 활용한 분석과 추천을 제공합니다.

### 주요 기능

- 📅 일정 관리: 할 일과 메모를 카테고리별로 관리
- 📊 분석: 일정과 메모를 기반으로 한 통계 및 분석
- 🤖 AI 챗봇: 사용자의 일정과 메모를 기반으로 한 맞춤형 추천
- 👤 프로필: 사용자 정보 및 설정 관리

## 🚀 팀원 소개

![9git9git 팀원들을 소개합니다!](https://github.com/user-attachments/assets/a1f5f257-1327-4215-9940-88c606301d87)

## 📚 저장소 구조

### 9git-frontend

> Next.js 기반의 프론트엔드 애플리케이션

- **기술 스택**: Next.js, TypeScript, Zustand, Tailwind CSS, shadcn-ui
- **주요 기능**: 회원가입/로그인, 일정 관리, 홈, 분석, 챗봇, 프로필
- **팀원**: 임헌찬(Lead), 윤소영, 윤정민

### 9git-backend

> FastAPI 기반의 백엔드 서버

- **기술 스택**: FastAPI, SQLAlchemy, Poetry, Uvicorn
- **주요 기능**: RESTful API, 데이터베이스 관리, 로깅 시스템
- **데이터베이스**: PostgreSQL (Azure Database for PostgreSQL)
- **팀원**: 김기덕(Lead), 이규호, 임헌찬, 배채은, 오동준

### 9git-ai

> AI 모델 및 서비스 관련 저장소

- **기술 스택**: Azure OpenAI
- **주요 기능**: AI 모델 통합, 챗봇 서비스
- **팀원**: 이규호(Lead), 김기덕, 배채은, 이희주

### 9git-devops

> DevOps 및 인프라 관리

- **기술 스택**: Docker, Azure Container Registry, Azure Container Apps
- **주요 기능**: CI/CD, 배포 자동화, 인프라 관리
- **팀원**: 김기덕(Lead), 이규호, 배채은

## 🚀 배포 환경

| 서비스 | URL | 상태 | 이모지 |
|--------|-----|------|--------|
| 프론트엔드 | https://gugit-frontend-test-aca.calmforest-521dd431.eastus.azurecontainerapps.io | 비활성화 | 🔴 |
| 백엔드 | https://gugit-backend-test-aca.calmforest-521dd431.eastus.azurecontainerapps.io | 비활성화 | 🔴 |

> 현재 배포 서비스는 비활성화 상태입니다.

## 🛠️ 기술 스택 상세

### 프론트엔드

- **Next.js 13+**: App Router를 사용한 서버 컴포넌트 기반 개발
- **TypeScript**: 정적 타입 시스템으로 안정적인 개발
- **Zustand**: 간단하고 빠른 상태 관리
- **Tailwind CSS**: 유틸리티 우선 CSS 프레임워크
- **shadcn-ui**: Radix UI 기반의 재사용 가능한 컴포넌트

### 백엔드

- **FastAPI**: 비동기 웹 프레임워크
- **SQLAlchemy**: ORM 및 데이터베이스 관리
- **Poetry**: 의존성 관리
- **Uvicorn**: ASGI 서버
- **PostgreSQL**: 관계형 데이터베이스
- **Alembic**: 데이터베이스 마이그레이션

### AI

- **Azure OpenAI**: GPT 모델 기반 챗봇 서비스
- **LangChain**: AI 모델 통합 및 프롬프트 관리

### DevOps

- **Docker**: 컨테이너화
- **Azure Container Registry**: Docker 이미지 저장소
- **Azure Container Apps**: 서버리스 컨테이너 배포
- **Azure Database for PostgreSQL**: 클라우드 데이터베이스
- **GitHub Actions**: CI/CD 파이프라인

## 📄 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다. 
