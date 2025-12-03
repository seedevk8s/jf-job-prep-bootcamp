# jf-job-prep-bootcamp

[![Java](https://img.shields.io/badge/Java-17%2B-red)](https://adoptium.net/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen)](https://spring.io/projects/spring-boot)
[![React](https://img.shields.io/badge/React-18-blue)](https://react.dev/)
[![MySQL](https://img.shields.io/badge/DB-MySQL-orange)](https://www.mysql.com/)
[![AWS](https://img.shields.io/badge/Cloud-AWS-yellow)](https://aws.amazon.com/)
[![Docker](https://img.shields.io/badge/Container-Docker-2496ED)](https://www.docker.com/)
[![GitHub](https://img.shields.io/badge/Git-GitHub-black)](https://github.com/)

Java 기반 풀스택 개발자로 취업하기 위한 **학습 로드맵 · 실습 코드 · 프로젝트 산출물**을 정리한 저장소입니다.  
이 저장소는 실무 개발자로 성장하기 위한 **웹 기초 → 자바 기초 → 백엔드 → 데이터베이스 → 클라우드/DevOps → 프로젝트 → 취업 준비**의 전체 흐름을 담고 있습니다.

---

## 📚 Curriculum Overview  

아래 학습 로드맵은 실제 풀스택 개발자 양성과정 커리큘럼 구조를 기반으로 구성하되,  
**웹 기초 → 자바 기초** 순으로 더 자연스러운 진입을 고려해 재배치했습니다.

### 1) Web Front-End (01_web_html_css_js / 04_react)
- HTML5 / CSS3 / JavaScript ES6+
- DOM 조작, 이벤트 모델, 비동기 처리
- React 기초 + SPA 개발
- 간단한 클론코딩 및 미니 프로젝트

### 2) Programming Foundations (Java Basic / Advanced)
- Java 문법 & OOP
- Interface / Exception / IO / Collection / Thread
- 실습 문제 및 코드 리뷰
- 예제 및 미니 프로젝트

### 3) Database & SQL (05_db_mysql)
- MySQL 기본 문법 및 ERD 설계
- JDBC / ORM(JPA, Hibernate)
- 실습: 도서관리, 회원관리, 게시판 DB 설계

### 4) Back-End Development (06_spring_boot)
- Spring Framework
- Spring Boot 3.x
- MVC, DI/IoC, AOP
- REST API & Controller 테스트(Postman / Rest Client)
- 로그인/회원가입/게시판 실습 프로젝트

### 5) Cloud & DevOps (07_cloud_devops)
- AWS EC2, RDS, S3
- Docker & Docker Compose
- Git / GitHub 협업
- CI/CD 개념 및 간단한 파이프라인 구성

### 6) Final Project (08_final_project)
- 팀 단위 웹서비스 개발
- ERD + API 문서 + 시연 영상 + 발표자료
- 코드 리뷰 및 기술면접 대비

---

## 🗺 전체 로드맵 (Mermaid)

```mermaid
graph TD;
    A[01 Web Front-End<br/>HTML/CSS/JS/React] --> B[02 Java Basic];
    B --> C[03 Java Advanced];
    C --> D[05 DB MySQL];
    D --> E[06 Spring Boot];
    E --> F[07 Cloud & DevOps];
    F --> G[08 Final Project];

