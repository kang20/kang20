# 강민기 
**Backend Developer**  

> 언제나 ‘왜’를 고민하는 개발자입니다.  
> 프로젝트 기능 개발 혹은 개선 과정에서 항상 유저 혹은 팀의 관점에서 이유를 탐구합니다.  
> 끝까지 해내는 실행력과 집요함에 자신 있습니다.  
> 기술 공유와 함께 성장하는 문화를 지향합니다.  

---

## 📇 Profile

- GitHub: https://github.com/kang20  
- Blog: https://kkangmg.tistory.com  
- Email: aorl2313@naver.com  
- Phone: 010-7107-5470  
- 생년월일: 2001.02.24  
- 군필  

---

## 🎯 핵심 역량

- 설계 · 구현 · 운영: Spring Boot, Spring MVC, Spring Security, Spring Cloud  
- 데이터베이스: MySQL, Redis (Pub/Sub), Kafka  
- 아키텍처 · DevOps: Docker, EC2, RDS, S3, Jenkins, GitHub Actions, Prometheus, Grafana, Loki  
- API 설계 · 최적화: Polling → SSE 마이그레이션, 커버링 인덱스, 쿼리 튜닝  
- 협업 · 커뮤니케이션: JIRA, Confluence, 기술 세미나 운영, 스터디 · 멘토링  

---

## 🚀 주요 프로젝트

### 1. 야밤 (Yabam)
대학교 축제를 위한 실시간 테이블 오더 애플리케이션  
- 기간: 2025.03.10 ~ 진행 중  
- 팀 구성: 프론트엔드 3명 / 백엔드 2명  
- 기술 스택: Spring MVC, Spring Cloud Gateway, Spring Security, JPA, MySQL, Redis, Kafka, PLG, Jenkins  

#### 🔍 프로젝트 개요
‘야밤’은 단기간 진행되는 대학교 축제의 현장에서 상용 테이블 오더 도입이 어려운 점을 해결하기 위해 개발된 애플리케이션입니다.  
QR 기반 주문, 점주용 PoS, 실시간 주문 조회 기능을 제공하며, 첫 시범 배포에서 Peak User 1,000명을 달성했습니다.  

#### 🏆 주요 성과
- 실제 대학 축제 점주들에게 직접 PT하여 사용 유치 성사  
- 첫 배포 Peak User 1,000명 달성  
- 실시간 주문 조회 방식 Polling → Server-Sent Events(SSE) 전환으로 RDB 부하 70% 감소, 평균 응답 지연 250ms → 60ms 개선  
- Kafka → Redis Pub/Sub 마이그레이션을 통해 메시징 지연 60% 감소  
- UUID v7 기반 QR 주문 세션 설계로 보안 강화, UX 개선  

#### ⚙️ 담당 및 기여
- 백엔드 아키텍처 설계 및 구현  
- 실시간 주문 처리 프로토콜 비교·도입 (Polling, SSE, Fetch API)  
- 메시징 시스템 최적화 (Kafka → Redis Pub/Sub)  
- 주문 세션 보안 강화 (UUID v7 커스텀 모듈 개발)  
- CI/CD 파이프라인 구축 및 운영 (Jenkins, Docker)  

---

### 2. To.duck (토덕)
성인 ADHD를 위한 일정·루틴·일기 관리 소셜 애플리케이션  
- 기간: 2024.05 ~ 진행 중  
- 팀 구성: 기획·디자인 2명 / iOS 2명 / 백엔드 3명  
- 기술 스택: Spring MVC, JPA, MySQL, Redis, GitHub Actions, JIRA  

#### 🔍 프로젝트 개요
‘토덕’은 성인 ADHD 사용자를 대상으로 일정 관리, 루틴 알림, 일기 기록, 커뮤니티 기능을 제공하는 생산성 앱입니다.  
출시 직후 App Store 생산성 부문 191위 달성.  

#### 🏆 주요 성과
- 반복 일정 데이터 폭증 문제 해결: 비트마스킹 + 부모·기록 이중 테이블 설계 도입  
- 범위 일정 조회 쿼리 튜닝: Covering Index + UNION ALL 적용으로 응답 지연 200ms → 70ms 단축  
- 아키텍처, 테스트, 린트 기반 CI 파이프라인 구축으로 코드 컨벤션 강화 및 리팩터링  

#### ⚙️ 담당 및 기여
- 반복 일정 모델링 및 테이블 설계  
- MySQL 쿼리 튜닝 및 인덱스 설계  
- 백엔드 테스트 환경 구축 및 CI/CD 파이프라인 운영  
- 프로젝트 전반 코드 리팩터링 및 성능 최적화  

---

## 🎓 학력 및 활동

- **국립금오공과대학교 컴퓨터공학과** (2020.03 ~ 2026.02, 재학 중)  
  - 전체 평점: 4.05/4.5, 전공 평점: 4.28/4.5  
- 멋쟁이사자처럼 대학 12기 부회장·백엔드 트랙장 (2024.01 ~ 2024.12)  
- IT 기술 세미나 “야밤의 금오톡” 운영 (2024.05 ~ 2025.04), 참여자 100명 달성  
- 교내 스터디 및 멘토링 진행  

---

## 🏅 수상 내역

- 2023 메타버스 경북 해커톤 우수상 (2등) — 재난 대피 시뮬레이션 애플리케이션  
- 2025 한국정보기술학회 은상 — 대학교 축제 활성화를 위한 테이블 오더 애플리케이션 (Polling → SSE Migration)  

---

## 📫 연락 및 링크

- GitHub: https://github.com/kang20  
- 블로그: https://kkangmg.tistory.com  
- 이메일: aorl2313@naver.com  
- 전화: 010-7107-5470  


[![Kang20 GitHub stats](https://github-readme-stats.vercel.app/api?username=Kang20)](https://github.com/Kang20/github-readme-stats)

