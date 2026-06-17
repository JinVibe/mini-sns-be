[English](#english) | [한국어](#korean)

<br>

<h1 id="english">📱 Mini SNS Backend Project (English)</h1>

This is a study-driven personal project aimed at cultivating **"pure backend engineering skills"** by deeply analyzing every aspect from scratch, without relying on AI code generators.

Moving beyond simply producing a finished product, the ultimate priority is training myself to articulate, **"Why was this technology chosen, and why was the architecture designed this way?"** at every single stage of development.

## 🎯 Core Project Goals
- **Deliberate Implementation**: Strictly avoid over-engineering and focus intensively on the core business logic of the service (Posts, Comments, Likes).
- **Solid Fundamentals & Architecture**: Establish a Test-Driven Development (TDD) rhythm and pursue a clean architecture based on the Separation of Concerns.
- **Architectural Responsibility**: Instead of rushing through feature implementation, continuously refine error handling, authorization validation, and the structural consistency of API responses.

## 🛠 Tech Stack
- **Language**: Java 21
- **Framework**: Spring Boot 3.x
- **Database**: H2 (Local Development & Testing) → PostgreSQL (Production Transition)
- **ORM**: Spring Data JPA
- **Validation**: Hibernate Validator
- **Authentication**: JWT (JSON Web Token)
- **Build Tool**: Gradle

## 📌 MVP Scope
This project strictly focuses on implementing the Minimum Viable Product (MVP) features for a text-based social network.

* **User Management**: Sign-up, Sign-in, Profile Retrieval
* **Post Management**: Create, Read (Detail/List with Pagination), Update, Delete
* **Social Interaction**: Comment Creation/Deletion, Post Like/Unlike
------------------------------------------------------------------------------
# 📱 Mini SNS Backend Project (Korean)

AI 코드 생성기에 의존하지 않고, 처음부터 끝까지 직접 고민하며 '순수 백엔드 엔지니어링 실력' 을 기르기 위한 스터디형 개인 프로젝트입니다.

단순히 완성된 결과물을 내는 것을 넘어, 코드가 작성되는 모든 과정에서 **"왜 이 기술을 선택했고, 왜 이렇게 구조를 설계했는가?"**를 스스로 설명할 수 있도록 훈련하는 것을 최우선 과제로 삼습니다.

## 🎯 프로젝트 핵심 목표
- **생각하는 구현**: 오버 엔지니어링을 철저히 배제하고, 서비스의 코어 비즈니스 로직(게시글, 댓글, 좋아요)에 집중합니다.
- **기본기 및 구조 확립**: TDD(테스트 주도 개발) 리듬을 적용하고, 관심사 분리(Separation of Concerns)를 통한 클린 아키텍처를 지향합니다.
- **설계 책임**: 기능 구현에 급급하지 않고 에러 처리, 권한 검증, API 응답 구조의 일관성을 끊임없이 점검합니다.

## 🛠 기술 스택 (Tech Stack)
- **Language**: Java 21
- **Framework**: Spring Boot 3.x
- **Database**: H2 (로컬 개발 및 테스트) → PostgreSQL (운영 전환)
- **ORM**: Spring Data JPA
- **Validation**: Hibernate Validator
- **Authentication**: JWT (JSON Web Token)
- **Build Tool**: Gradle

## 📌 기능 범위 (MVP Scope)
현재 프로젝트는 텍스트 기반 소셜 네트워크의 최소 기능(MVP) 구현에 집중합니다.

* **회원 관리**: 회원가입, 로그인, 내 정보 조회
* **게시글 (Post)**: 게시글 작성, 수정, 삭제, 상세 및 목록 조회 (페이지네이션 적용)
* **소통 (Interaction)**: 댓글 작성 및 삭제, 게시글 좋아요 추가 및 취소