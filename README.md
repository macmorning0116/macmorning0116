 ## Hi There 👋🏻


### Now I'm learning..
<div>
<img src="https://img.shields.io/badge/Spring Framework-6db33f?style=flat-square&logo=Spring&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-3776AB?style=flat-square&logo=Java&logoColor=white"/> 
<img src="https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/JPA-6DB33F?style=flat-square&logo=JPA&logoColor=white"/>  
<br>
<img src="http://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-red?style=flat-square&logo=Redis&logoColor=white"/>
<img src="http://img.shields.io/badge/GitHub Actions-2088FF?style=flat-square&logo=GitHub Actions&logoColor=white"/>
<br>
<div>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=black"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>
</div>

### Project
<details>
  <summary><b>Basstargram (AI 낚시 포인트 추천 및 조행 커뮤니티 서비스)</b></summary>

  - Playwright 기반 크롤러를 구축해 **네이버 카페 조행 데이터 수집 파이프라인 설계**
  - 게시판 3종 데이터를 **RDS(PostgreSQL) 원본 저장 + OpenSearch 검색 인덱스** 구조로 분리 적재
  - S3와 Amazon OpenSearch Service custom package를 활용한 **동의어 사전 구축**
  - `bass ↔ 배스`, `프리 ↔ 프리리그`, `스베 ↔ 스윔베이트` 등 **영문/국문 혼용 표현과 낚시 은어·축약어 검색 지원**
  - 로그 집계, 메일 알림, 중복 기준 종료 조건을 적용한 **크롤링 운영 안정화**
  - **Grafana Cloud 기반 로그/메트릭 관측 시스템 구축** (EC2 리소스 사용량 월 고정 비용 18.99 달러 감축)
  - 피드 목록 **경량 DTO + JOIN FETCH N+1 해결** (23쿼리 → 2쿼리), 복합 인덱스 적용
  - **커서 기반 페이지네이션** (게시글/댓글/검색), Caffeine 캐시 (날씨/지오코딩 5분 TTL)
  - Thumbnailator 기반 **썸네일 자동 생성** (400px) + S3 **CompletableFuture 병렬 업로드**
  - **TanStack Query v5 도입** — API 캐싱, 옵티미스틱 업데이트, 탭 전환 시 즉시 표시
  - Spotless + **Checkstyle 도입** (Google Style 기반 코드 컨벤션 자동 검사)
  - Flyway DB 마이그레이션 (V1~V6), **PostGIS** 공간 데이터 지원
  - GitHub Actions, GHCR, Docker를 활용한 **CI/CD 파이프라인 구축**
  - JUnit + Mockito를 활용한 **테스트 코드 작성** (Line Coverage 91.11%)
  - 실시간 위치 기반 날씨 API + 사진 데이터 + GPT API를 활용한 포인트 및 채비 추천
  - 네이버 지도 API 연동
  - 🔗 Link: https://www.ai-fishing.store/
  - 🔗 GitHub Repo: https://github.com/macmorning0116/my-fishing-server

</details>


<details>
 <summary><b>소문 (소규모 공연 예약 커뮤니티 플랫폼)</b></summary>
 
 - 사용자 맞춤 공연 조회 구현 및 SQL 쿼리 튜닝을 통한 **성능 65% 개선** (200ms → 70ms)
 - 실시간 인기 공연 조회 기능 구현, **Redis 캐싱 + 스케줄링으로 TPS 74.7 → 6084 / 평균 응답 시간 1302ms → 9ms**
 - Embedded Redis를 통한 개발 환경 구성
 - JavaMailSender와 Thymeleaf를 이용한 **SMTP 기반 이메일 인증**
 - OAuth 2.0 + JWT를 활용한 **소셜 로그인** 개발
 - React 기반 **홈 화면, 회원가입, 로그인 UI 개발**
 - 🔗 GitHub Repo: https://github.com/prgrms-be-devcourse/NBE1_2_Team05
 
</details>

<details>
  <summary><b>미어켓 (직거래 기반 중고물품 블라인드 입찰 서비스)</b></summary>

  - 서비스 장애 복구 및 입찰 마감 자동화 프로세스 설계 및 구현 (**Quartz Scheduler 활용**)
  - Redis의 SETNX와 TTL을 이용하여 **동시성과 중복방지(따닥이슈)를 보장하는 입찰 시스템** 설계 및 구현
  - STOMP + Redis + MongoDB + FCM을 활용한 **실시간 채팅 시스템** 설계 및 구현
  - Docker Compose를 이용한 **운영 환경 구성**
  - **멀티 모듈 구조**로 확장성과 유지보수성 강화
  - 🔗 GitHub Repo: https://github.com/J1P5/Meerket__BE

</details>




### Experience
* Programmers Back-end Dev Course 1st (2024.07 ~ 2024.12)

<!--![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=ekffuqhwk)-->
