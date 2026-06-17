[English](#english-scope) | [한국어](#korean-scope)

<br>

<h1 id="english-scope">🎯 Project Scope: DevOps & MLOps Track (English)</h1>

## 1. Project Vision
The goal is to build a high-quality, production-ready Mini SNS backend within 12 weeks. Instead of adding superficial features, this project prioritizes **System Reliability, Automated Pipelines (CI/CD), and Data Flow**, which are the foundations of DevOps and MLOps.

## 2. Feature & Infrastructure Scope

| Category | Item | Description & Architectural Reason |
| :--- | :--- | :--- |
| **🟢 Essential (In-Scope)** | User Management | Signup, Login(JWT), My Profile. |
| | Post CRUD | Core business logic for data generation. |
| | Social Actions | Comments & Likes (Foundation for data interaction). |
| | **Trending Posts** | **MLOps Foundation**: Calculating popularity based on 'Likes' and 'Time'. |
| | **Search** | **Data Engineering**: Implementing basic indexing and query optimization. |
| | **CI/CD Pipeline** | **DevOps**: Automated testing and deployment via GitHub Actions. |
| | **Cloud Infrastructure** | **AWS**: Deploying on EC2 with RDS (PostgreSQL). |
| **🟡 Optional** | Monitoring | Metrics collection via Prometheus & Grafana. |
| | Follow System | Social graph modeling (only if core tasks are finished). |
| **🔴 Excluded (Out-of-Scope)** | Image Upload | Avoid infrastructure overhead (S3/CDN) for this phase. |
| | Real-time Features | Avoid WebSocket complexity; focus on stateless scalability. |
| | MSA / Kafka | Avoid over-engineering; focus on solid Monolithic stability first. |

---

<h1 id="korean-scope">🎯 프로젝트 범위: DevOps & MLOps 트랙 (한국어)</h1>

## 1. 프로젝트 비전
12주 안에 실제 운영 가능한 수준의 Mini SNS 백엔드를 구축합니다. 화려한 기능을 늘리기보다 **시스템의 신뢰성, 자동화된 파이프라인(CI/CD), 그리고 데이터의 흐름**이라는 DevOps 및 MLOps의 기초를 다지는 데 집중합니다.

## 2. 기능 및 인프라 범위

| 구분 | 항목 | 설명 및 설계 이유 |
| :--- | :--- | :--- |
| **🟢 필수 (In-Scope)** | 회원 관리 | 회원가입, 로그인(JWT), 내 정보 조회. |
| | 게시글 CRUD | 데이터 생성을 위한 핵심 비즈니스 로직. |
| | 소셜 액션 | 댓글 및 좋아요 (데이터 상호작용의 기초). |
| | **인기글 (Trending)** | **MLOps 기초**: '좋아요'와 '시간' 기반의 데이터 가공 및 서빙. |
| | **검색 (Search)** | **데이터 엔지니어링**: 기본적인 인덱싱 및 쿼리 최적화 경험. |
| | **CI/CD 파이프라인** | **DevOps**: GitHub Actions를 통한 자동 테스트 및 배포 구축. |
| | **클라우드 인프라** | **AWS**: EC2 서버 및 RDS(PostgreSQL) 데이터베이스 운영. |
| **🟡 선택 (Optional)** | 모니터링 | Prometheus와 Grafana를 통한 시스템 메트릭 수집. |
| | 팔로우 시스템 | 소셜 그래프 모델링 (필수 기능 완료 시 진행). |
| **🔴 제외 (Out-of-Scope)** | 이미지 업로드 | S3/CDN 등 인프라 설정 오버헤드 방지를 위해 제외. |
| | 실시간 기능 | 웹소켓 복잡도를 피하고 무상태(Stateless) 확장성에 집중. |
| | MSA / Kafka | 오버 엔지니어링 방지; 단단한 모놀리식 안정성 우선. |