# 프로젝트

## SimpleScaffold 보일러플레이트

> https://github.com/SimpleScaffold

다양한 프로젝트 경험에서 반복되는 설정을 체계화한 조직 단위 보일러플레이트 모음.  
**배포시간 5분 → 30초** 단축, 일관된 UI/UX 체계 확립.

| 레포지토리 | 설명 |
|-----------|------|
| ss-front-boilerplate-vite-ts | React + Vite + Redux + shadcn (TypeScript) |
| ss-front-boilerplate-next-ts | Next.js (TypeScript) |
| ss-front-boilerplate-vite-js | React + Vite (JavaScript) |
| ss-mfa-boilerplate-host | Micro Frontend 호스트 앱 |
| ss-mfa-boilerplate-remote | Micro Frontend 리모트 앱 |
| ss-mfa-boilerplate-shell | Micro Frontend 셸 |
| ss-infra-mediaServer-nginx | 정적 미디어 파일 서빙 + 비디오 스트리밍 Nginx 서버 |
| ss-data-db-docker | Docker Compose 기반 DB 구성 |
| ss-security-toolkit | 보안 도구 모음 |
| ss-design-krds | 디자인 시스템 (KRDS 기반) |
| ss-plan-doc-md | 기획 문서 템플릿 |

---

## 회사 프로젝트 목록

### 온품

| 프로젝트 | 기간 | 기술 스택 |
|---------|------|----------|
| 3D 지도 플랫폼 (디지털 트윈) | 2025.10 ~ 현재 | React, Cesium |

**Cesium 지도 성능 개선 주요 수치:**

| 지표 | 개선 전 | 개선 후 |
|------|--------|--------|
| JS Heap 노드 수 | 52,179개 | 20,674개 (−60%) |
| JS Heap 크기 | 2.45 MB | 0.35 MB (−86%) |
| 3D Tiles 스타일 조건 | ~5,000개 | ~10–20개 (−99%) |
| POI 가시성 갱신 (이동 중) | 15회/초 | 0회/초 |

---

### 유클리드소프트

| 프로젝트 | 기간 | 기술 스택 | 주요 성과 |
|---------|------|----------|----------|
| LLM 시각화 공통 템플릿 (LimeLab) | 2025.04 ~ | React, Django, MariaDB | 스토리북/디자인 시스템 도입, 스트리밍 응답 처리 |
| 심층망 암호화 키관리장치 (SecuAI) | 2025.02 ~ 2025.03 | Django, Docker, Ubuntu, MariaDB | Docker 도입으로 배포 자동화 |
| 사내 MLOps 구축 | 2025.01 ~ 2025.03 | React, Spring, PostgreSQL, Kubeflow, LakeFS, MinIO | 사용자/프로젝트별 리소스 관리 체계 구축 |
| 유성구청 예산·회계 업무가이드 플랫폼 | 2025.01 ~ 2025.03 | React, Django | AI 챗봇으로 업무 담당자 교체 시 효율성 제고 |
| KGS LLM VOC 플랫폼 | 2024.09 ~ 2024.12 | React, Langchain, Python | Bllossom 모델 연동 기반 사용자 상호작용 처리 |
| 대전 0시축제 CCTV 관제 플랫폼 | 2024.07 ~ 2024.08 | React, Node.js | 네이버 지도 기반 CCTV 위치 표시 및 지하철 연결정보 시각화 |
| KISTEP 통합연구지원시스템 (1·2차) | 2023.07 ~ 2024.12 | React, D3, Django, Docker, ElasticSearch | Lighthouse 45→95, 배포 5분→30초, 개발 서버 로딩 1분→1초 |
| RCMS 정보·통계 활용성 제고 | 2023.11 ~ 2024.01 | 전자정부프레임워크, Websquare, Java | 연구비 집행·정산 고도화 |
| 인사관리 시스템 (LIME-HRM) | 2023.03 ~ 2023.08 | React, Django | 설문·간트차트·CMS 게시판·직무관리 기능 |
