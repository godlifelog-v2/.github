# godlifelog-v2

> 갓생로그 V2 개발 조직입니다.  
> 루틴 관리 기반의 생산성 웹 서비스 **갓생로그**의 차기 버전을 개발합니다.

---

## 🚀 프로젝트 소개

**갓생로그**는 사용자가 루틴을 설정하고 꾸준히 실천하며 갓생을 기록하는 웹 서비스입니다.  
V2에서는 프론트엔드를 앱 기반 모바일 UI로 전환하고, 백엔드 기능을 대폭 고도화합니다.

- 🌐 서비스 URL: [godlifelog.com](https://godlifelog.com)

---

## 📁 레포지토리 구성

| 레포 | 설명 | 기술 스택 |
|---|---|---|
| [godlifelog-backend](https://github.com/godlifelog-v2/godlifelog-backend) | REST API 서버 | Java, Spring Boot, MyBatis, Redis |
| [godlifelog-frontend](https://github.com/godlifelog-v2/godlifelog-frontend) | 모바일 웹 클라이언트 | React |

---

## 🛠️ 기술 스택

### Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat&logo=socketdotio&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat&logo=amazon-aws&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

---

## ✨ V2 주요 변경 사항

### 신규 기능
- 🤖 **루틴 한 줄 일기** — AI API 연동
- 🎯 **루틴 추천 로직** — 사용자 패턴 기반 추천
- 💬 **1:1 문의 실시간화** — HTTP → WebSocket 전환
- ⏱️ **챌린지 리얼타임 인증** — 스톱워치 기반 실시간 시간 인증
- 🔄 **챌린지 자동화** — 리젠용 챌린지 랜덤 활성화

### 개선 사항
- 📱 **앱 기반 모바일 UI** — 반응형 웹 → 모바일 전용 레이아웃 (React)
- 🔀 **API 버전 관리** — 전체 엔드포인트 `/api/v1/` prefix 적용
- 🔔 **알림 기능** — SSE 기반 실시간 알림 (검토 중)
- 🔐 **OAUTH2 소셜 로그인** (검토 중)

---

## 👥 팀원

| 이름 | 역할 | 담당 |
|---|---|---|
| 희만 | Backend / Frontend | 루틴 추천, 1:1 웹소켓, 홈·마이페이지·FAQ 프론트 |
| 용기 | Backend / Frontend | 챌린지 고도화, 한 줄 일기 AI, QNA·어드민·챌린지 프론트 |

---

## 📋 협업 방식

- **이슈 트래킹**: [Notion](https://steadfast-bakery-f61.notion.site/32ddd4b2a54181e89218c890f3134517?source=copy_link) — 스프린트 태스크, 이슈, PR 리뷰 관리
- **브랜치 전략**: GitHub Flow
```
  main         — 운영 배포 브랜치
  dev      — 개발 통합 브랜치
  feat/{name}  — 기능 개발 브랜치
  fix/{name}   — 버그 수정 브랜치
```
- **스프린트**: 2주 단위
- **코드 리뷰**: PR 생성 후 상대방 Approve 시 머지

---

## 🔗 관련 링크

- 📌 [Notion 대시보드](https://steadfast-bakery-f61.notion.site/32ddd4b2a54181e89218c890f3134517?source=copy_link) — 태스크 및 회의록 관리
- 🌐 [godlifelog.com](https://godlifelog.com) — 운영 서비스
