# 백엔드 개발자 정수민입니다 👋

<br>

## 🛠 Tech Stack

**Backend**
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA_·_QueryDSL-59666C?style=flat-square&logo=hibernate&logoColor=white)

**Data · Messaging**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Infra · Test**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3F?style=flat-square&logo=testcontainers&logoColor=white)

<br>

## 📌 Projects

### [토닥토닥 (Todak-Todag)](https://github.com/Todak-Todag/server) · 2026.08 – 09 · 6인
퇴원 후 돌봄을 지역 제공자와 자동 매칭·관리하는 Spring MSA 케어 플랫폼
**Provider 서비스 담당** (서비스 커밋 97%)

- 겹침 검사 단일 쿼리 전환 → **처리량 110 → 163 TPS, 50스레드 오류율 27.31% → 0%** (JMeter)
- Outbox 패턴으로 매칭 결과 이벤트 유실 차단, DLQ · 멱등 처리로 재시도 소진 메시지 보존
- 부모 행 비관적 락으로 일정 쓰기 동시성 제어 (Testcontainers 동시성 통합 테스트)
- 게이트웨이 서명 JWT(RS256) 검증으로 헤더 위조 인증 경로 제거

### [물류 관리 · 배송 시스템](https://github.com/1010-2-Logistics/logistics) · 2026.08 · 5인
허브 간 최단 경로로 배송을 생성·추적하는 MSA 물류 플랫폼
**Delivery 서비스 · 인프라 담당** (서비스 커밋 99%)

- 서비스 간 호출의 응답 유실과 확정 실패를 구분해 소속 동기화 정합성 유지
- Swagger 라우트 추가로 사라진 업무 라우트 10개 복구 + 라우팅 회귀 테스트 12케이스
- Terraform(VPC · EC2 · ECR · OIDC) + GitHub Actions 배포 파이프라인 구축

### [Delivery](https://github.com/yonghyun0325/delivery) · 2026.07 · 6인
회원·가게·주문·결제·리뷰·AI 메뉴 생성을 갖춘 Spring Boot 음식 주문 플랫폼
**가게 · 지역 · 카테고리 도메인 담당**

- 역할 + 소유권 이중 검증으로 IDOR 차단 (단위 테스트 6건)
- QueryDSL 동적 검색, 가게 소프트 삭제 시 하위 데이터 연동

### [Howscat](https://github.com/summmmmmmin/Howscat_backend) · 개인 프로젝트
고양이 건강 관리 Android 앱의 Spring Boot API 서버
- magic bytes 기반 이미지 업로드 검증, GitHub Actions → EC2 자동 배포

<br>

## 📫 Contact
[![Email](https://img.shields.io/badge/jsoomin01@naver.com-03C75A?style=flat-square&logo=naver&logoColor=white)](mailto:jsoomin01@naver.com)
