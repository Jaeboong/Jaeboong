<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=5394F6&height=190&section=header&text=Jaehwan%20Kim&fontSize=42&fontColor=ffffff&desc=Back-End%20%C2%B7%20AI%20Agent%20%C2%B7%20Infra%20Ops&descSize=16&descAlignY=58)

### 문제를 구조로 만들고, 반복되는 구조를 에이전트로 자동화합니다.

백엔드와 AI 에이전트를 설계하고 컨테이너 기반 인프라까지 직접 운영하는 개발자 **김재환**입니다.
기술 자체보다 실제 사용자의 업무 흐름과 운영상의 병목에서 문제를 정의합니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-jaeboong.shop-5394F6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://jaeboong.shop/PF/)
[![Email](https://img.shields.io/badge/Email-cbkjh0225%40gmail.com-3C4149?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cbkjh0225@gmail.com)

</div>

## What I Build

- **AI Workflow** — 사람에게 집중된 반복 업무를 역할과 단계로 분해해 에이전트 워크플로우로 구현
- **Back-End** — API·데이터 모델·트랜잭션 정합성을 중심으로 서버 설계
- **Infra Ops** — Docker 기반 배포, 모니터링, 로그 분석과 장애 대응 자동화

## Featured Projects

### 자소전 — 멀티에이전트 자기소개서 작성 지원 서비스

[Repository](https://github.com/Jaeboong/Jasojeon) · [Service](https://xn--9l4b13i8j.com) · **[프로젝트 상세보기](project/JASOJEON.md)**

지원자가 여러 문서와 사이트를 오가며 수행하던 **공고 분석 → 기업 조사 → 경험 연결 → 작성 → 검토** 과정을 하나의 AI 워크플로우로 재설계했습니다.

- Claude·Codex·Gemini를 Coordinator·Drafter·복수 Reviewer·Finalizer 역할에 배정
- 실행 중 사용자 지시를 반영하고 중단 지점부터 이어가는 Human-in-the-loop 구현
- DART·웹·채용공고·Notion·개인 경험 문서를 출처와 목적에 따라 작성 컨텍스트로 연결
- 공고 파서 사실 필드 인식률 **27.3% → 43.8%**, ATS 오인식 **32건 → 0건**으로 개선

`TypeScript` `React` `Fastify` `WebSocket` `PostgreSQL` `Redis` `Docker` `MCP`

---

### TODO 앱 AI 인프라 어시스턴트 (DoitDo)

[NanoClaw Fork](https://github.com/Jaeboong/nanoclaw/tree/doitdo) · **[프로젝트 상세보기](project/DOITDO_AI_INFRA.md)**

Play Store와 App Store에 배포한 TODO 앱의 백엔드 개발에 참여하고, 인프라 담당자에게 집중된 운영 업무를 팀이 자연어로 수행할 수 있도록 NanoClaw를 커스텀해 도입했습니다.

- Discord에서 서버 상태·Docker 로그·데이터와 프로젝트 정보를 자연어로 조회
- Prometheus·Loki·Grafana 경보를 받아 메트릭·로그·코드베이스 기반으로 원인과 대응 방안 분석
- 장애 감지 → 담당자 호출 → 분석 → 팀 공유 흐름과 일간·주간·월간 운영 리포트 자동화
- 그룹별 컨테이너 격리, 권한별 마운트, 발신자 제한과 시크릿 차단 적용

`TypeScript` `Node.js` `Discord.js` `Docker` `Prometheus` `Loki` `Grafana` `Jira` `GitLab`

---

### Campung — 위치 기반 캠퍼스 커뮤니티

[Backend Repository](https://github.com/Jaeboong/Campung_Backend) · **[프로젝트 상세보기](project/CAMPUNG.md)** · **신한은행 해커톤 with SSAFY 대상**

- 5인 팀에서 백엔드·인프라 단독 담당
- Redis 24시간 슬라이딩 윈도우 기반 HOT 게시글 실시간 집계
- GPT 감정 분석 결과를 캠퍼스 온도·날씨로 변환해 시각화
- Docker·GitHub Actions·SSH 기반 자동 배포와 헬스체크 구성

`Java 17` `Spring Boot` `MariaDB` `Redis` `AWS S3` `Docker` `GitHub Actions`

---

### HearBe — 시각장애인 음성 쇼핑 지원 서비스

[Repository](https://github.com/Jaeboong/hearbe) · **[프로젝트 상세보기](project/HEARBE.md)**

- 규칙 기반 즉시 응답과 KoELECTRA 분류를 결합한 음성 명령 NLU 파이프라인 설계
- 회원가입·결제·환불 등 쇼핑 명령 의도 분류, 평균 응답시간 **23ms** 달성

`Python` `PyTorch` `KoELECTRA` `Hugging Face`

---

### MOA — 금융 Open API 기반 목표·예산 관리 서비스

[Repository](https://github.com/Jaeboong/MOA) · **[프로젝트 상세보기](project/MOA.md)**

- 외부 금융 API와 로컬 DB의 계좌·거래 데이터를 동기화하는 정합성 로직 구현
- 월간 수입을 목표·고정비·주간 예산으로 배분하고 부족분을 자동 조정하는 흐름 설계

`Java 17` `Spring Boot` `PostgreSQL` `Redis` `Docker`

## Tech Stack

### AI · Agent

![Claude](https://img.shields.io/badge/Claude-191919?style=flat-square&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-000000?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=111)
![MCP](https://img.shields.io/badge/MCP-5394F6?style=flat-square)

### Back-End · Data

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### Infra · Operations

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=111)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

## Experience

- **SSAFY 14기** · Java·Spring Boot·DB·RAG·LLM·AI Agent 교육 및 팀 프로젝트 `2025.07 – 2026.06`
- **고려대학교 세종캠퍼스** · 컴퓨터융합소프트웨어학과 학사 `2019.03 – 2025.08`
- **SQLD** · 한국데이터산업진흥원 `2024.09`
- **OPIc IM2** `2026.03`
