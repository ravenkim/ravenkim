# 기술 스택

---

## 역량 요약

**Overall**
- 직관적인 유저 인터페이스 및 애니메이션 구현을 좋아합니다.
- 회사 혹은 팀의 프로세스 및 문화를 개선하려는 시도를 적극적으로 합니다.
- 개발 환경, 코드 구조를 개선하거나 표준화하기를 좋아합니다.
- 최고의 기술보다는 상황에 맞는 기술을 선택하여 적용합니다.
- 업무에 필요하다면 익숙하지 않은 분야도 적극적으로 탐색하여 결과를 만들어냅니다.

**Communication**
- 다양한 사회경험을 통해 커뮤니케이션에 능숙합니다.
- 일정 산정, 진행 상황 공유, 이슈 관리에 능숙하며 상황에 맞는 협업 툴을 활용합니다.
- 프로젝트 초기 설계부터 배포 및 유지보수까지 커뮤니케이션을 통해 원활히 조율합니다.

**Web**
- 다양한 OS 및 브라우저를 지원할 수 있습니다.
- 모바일 브라우저에서의 트러블 슈팅이 가능합니다.
- 다양한 SI 경험을 통해 여러 웹 프레임워크에 능숙합니다.

**Security**
- K-Shield Jr.를 수료하여 웹 보안 취약점에 대한 이해를 바탕으로 안전한 코드를 작성합니다.
- 인증·인가 시스템 공통화, 키 관리 플랫폼 구축, 배포 서버 보안 환경 설계 경험이 있습니다.

**JavaScript**
- JavaScript와 TypeScript에 능숙하며 Node.js 생태계의 툴링에 익숙합니다.
- 다양한 패키지 매니저를 활용하며, 특히 Yarn Berry를 가장 잘 다룹니다.
- 빌드 도구를 통한 트리 셰이킹, 코드 스플리팅 등 최적화 기법 적용 경험이 있습니다.

**React**
- React hooks를 적극 활용하며 함수형 컴포넌트 위주로 구현합니다.
- Vite를 이용한 빠른 SPA 개발 환경 구축과 Next.js 기반 CSR 구현에 능숙합니다.
- 상태 관리, UI/UX 개선, 공통화된 코드 구조 설계, boilerplate 고도화 경험이 있습니다.

**DevOps**
- Docker, Ubuntu 서버 구축, 배포 자동화 및 운영 서버 관리 경험이 있습니다.
- CI/CD 구성, 서버 및 DB 구축, 배포 속도 최적화, 반복 업무 자동화 등 DevOps 전반 경험이 있습니다.

---

## AI 개발 도구

Cursor와 Claude Code를 단순 코드 생성기가 아닌 구조적 실행 파트너로 활용합니다. 탐색 → 계획 → 실행 → 검증의 4단계 사이클을 적용하고, 큰 작업은 Phase 단위로 분할합니다. 팀 규칙과 디자인 시스템은 `.cursor/rules`에 탑재해 일관성을 자동으로 유지합니다.

| 도구 | 활용 방식 |
|------|----------|
| Cursor | 하네스 코딩 방식 — `.cursor/rules` 기반 규칙 관리, Plan Mode 계획 수립, Phase 단위 실행 |
| Claude Code | 에이전트 루프 방식 — 탐색 → 계획 → 실행 → 검증 4단계 사이클 실무 적용 |
| GitHub Copilot | 코드 완성·리뷰·테스트 케이스 보조 |

---

## Core Frontend

| 기술 | 경험 |
|------|------|
| TypeScript | 전 직장 Main 언어, 보일러플레이트 기본 스택 |
| JavaScript | 4년+ 실무, JS/TS 병행 |
| React | 주력 프레임워크, 9개+ 프로젝트 |
| Redux Toolkit | 보일러플레이트 기본 탑재, 실무 전반 |
| TanStack Query | 실무 다수 활용 |
| Zustand | 실무 활용 |
| Redux Saga / Redux / Recoil | 실무 경험 |
| Axios / Fetch / RTK Query | API 통신 전반 |
| Next.js | 보일러플레이트 보유, 실무 CSR 구현 |
| React Router v7 / App Router | 실무 활용 |

## 디자인 시스템

디자인을 수치 기반 공식으로 정의해 AI 코딩 도구가 일관되게 적용할 수 있도록 문서화합니다.

| 항목 | 내용 |
|------|------|
| 색상 설계 | 6:3:1 비율 법칙, HSL 팔레트 구성, 텍스트-배경 대비 접근성 4.5+ 기준 |
| 레이아웃 | 8px 기반 그리드, 반응형 컬럼 시스템 (데스크톱 12 / 태블릿 8 / 모바일 4) |
| 컴포넌트 | shadcn/ui + KRDS 기반 디자인 시스템 구축 (ss-design-krds) |
| 문서화 | Storybook 도입·운영, `.cursor/rules`에 디자인 규칙 탑재 |

## UI / Styling

| 기술 | 경험 |
|------|------|
| Tailwind CSS | 보일러플레이트 기본 스택, 전 직장 전반 |
| SCSS | 다수 프로젝트 |
| shadcn/ui | 보일러플레이트 기본 탑재 |
| Ant Design | 실무 다수 활용 |
| Emotion / styled-components / vanilla-extract | CSS-in-JS 실무 경험 |
| Storybook | LimeLab 프로젝트에서 도입·운영 |

## Build & DX

| 기술 | 경험 |
|------|------|
| Vite | 보일러플레이트 주력 빌드 도구 |
| Yarn Berry | 주력 패키지 매니저 |
| ESLint / Prettier | 모든 프로젝트 기본 설정 |
| Webpack | 트리 셰이킹·코드 스플리팅 최적화 |
| Rollup | 라이브러리 빌드 경험 |
| React / Redux / TanStack Query DevTools | 디버깅 기본 도구 |

## 시각화

| 기술 | 경험 |
|------|------|
| D3.js | KISTEP 다차원 네트워크 시각화 |
| Cesium | 온품 3D 지도 플랫폼, JS Heap −86% 성능 최적화 |

## Backend (Sub)

| 기술 | 경험 |
|------|------|
| Django | 다수 프로젝트 Sub 스택 |
| FastAPI | 실무 경험 |
| Node.js / Express | CCTV 관제 프로젝트 |
| NestJS | 실무 경험 |
| Spring | KISTEP, RCMS 프로젝트 |

## Database

| 기술 | 경험 |
|------|------|
| MariaDB | 다수 프로젝트 |
| PostgreSQL | MLOps, KISTEP 등 |
| MongoDB | 실무 경험 |
| Prisma / Django ORM | ORM 실무 활용 |

## DevOps

| 기술 | 경험 |
|------|------|
| Docker / Docker Compose / Podman | 배포 자동화, 보일러플레이트 포함 |
| Nginx / Gunicorn | 보일러플레이트 미디어 서버 직접 구성, WSGI 서버 운영 |
| GitHub Actions | CI/CD 다수 구성 |
| Prometheus / Grafana | 모니터링·로깅 |
