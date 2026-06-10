# 기술 스택

---

## AI 개발 도구

Cursor와 Claude Code를 실무의 핵심 개발 도구로 활용합니다. 단순히 코드를 생성하는 용도가 아니라, 탐색 → 계획 → 실행 → 검증의 4단계 사이클 안에서 구조적 실행 파트너로 사용합니다. 큰 작업은 Phase 단위로 분할하고, 팀 규칙과 디자인 시스템은 `.cursor/rules` 파일에 탑재해 AI가 새 코드를 생성할 때도 일관된 기준을 따르도록 구성합니다. GitHub Copilot은 코드 완성·리뷰·테스트 케이스 작성을 보조하는 용도로 병행합니다.

---

## Core Frontend

React와 TypeScript를 주력 스택으로 3년 이상 실무에서 사용해왔습니다. 상태 관리는 프로젝트 규모와 요구사항에 따라 Redux Toolkit, TanStack Query, Zustand를 선택적으로 적용합니다. Next.js는 보일러플레이트를 직접 구축해 운영했으며, React Router v7은 SPA 라우팅 설계에 활용합니다.

## 디자인 시스템

디자인을 수치 기반 공식으로 정의해 일관성을 유지합니다. 색상은 6:3:1 비율 법칙과 HSL 팔레트로 구성하고, 텍스트와 배경의 대비는 접근성 기준인 4.5 이상을 충족하도록 설계합니다. 레이아웃은 8px 단위 그리드와 반응형 컬럼 체계(데스크톱 12 / 태블릿 8 / 모바일 4)로 정의합니다. 컴포넌트 라이브러리는 shadcn/ui와 KRDS 기반으로 구축했으며(ss-design-krds), Storybook으로 문서화합니다. 이 규칙들을 `.cursor/rules`에 탑재해 AI 코딩 도구가 새 컴포넌트를 만들 때도 시스템을 자동 준수하도록 연결합니다.

## UI / Styling

스타일링은 Tailwind CSS를 기본으로 사용하며, 보일러플레이트의 기본 스택으로 채택해 전 직장 대부분의 프로젝트에 적용했습니다. SCSS는 다수 프로젝트에서 구조적 스타일 분리에 활용했고, Emotion·styled-components, vanilla-extract는 실무에서 경험했습니다.

## Build & DX

빌드 도구는 Vite를 주력으로 사용하며, 보일러플레이트의 기본 구성으로 적용했습니다. 패키지 매니저는 Yarn Berry를 사용하고, ESLint·Prettier는 모든 프로젝트에 기본 설정합니다. Webpack은 트리 셰이킹과 코드 스플리팅 최적화 경험이 있으며, Rollup은 라이브러리 빌드에 활용했습니다.

## 시각화

D3.js로 KISTEP 프로젝트의 다차원 네트워크 그래프를 구현했고, Cesium으로 온품의 3D 디지털 트윈 지도 플랫폼을 구축했습니다. Cesium에서는 JS Heap을 86% 줄이고 3D Tiles 스타일 조건을 99% 감소시키는 성능 최적화를 직접 수행했습니다.

## Backend (Sub)

프론트엔드 주력이지만, 프로젝트 전반을 담당하는 과정에서 백엔드 경험도 쌓았습니다. Django는 다수 프로젝트에서 Sub 스택으로 활용했으며, Spring은 KISTEP·RCMS 프로젝트에서 사용했습니다. FastAPI, Node.js/Express, NestJS도 실무에서 경험했습니다.

## DevOps

Docker와 Docker Compose는 배포 자동화와 보일러플레이트 환경 구성에 사용하며, Nginx는 미디어 서버를 직접 구성해 보일러플레이트에 포함했습니다. GitHub Actions로 CI/CD 파이프라인을 다수 구성했습니다.
