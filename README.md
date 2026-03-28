### 정재원 | FE

실서비스에서 로그인, API 응답, 예외 상황으로 사용자가 멈추는 지점을 화면에서 해결해온 프론트엔드 개발자입니다.  
React와 TypeScript를 기반으로 인증 분기, 상태 관리, 라우팅 조건을 설계하고, 운영 중 발생한 이슈는 요청과 로그를 함께 보며 원인 구간을 좁혀왔습니다.

[포트폴리오](https://aes-portfolio-app.vercel.app/#about) | [GitHub](https://github.com/wonis1) | [이메일](mailto:wjdwo2808@gmail.com)

---

### 대표 프로젝트

### RE:CALL
<p align="center">
  <img src="./assets/recall-thumbnail.png" alt="RE:CALL login page thumbnail" width="720" />
</p>

동창생 탐색 웹 서비스 | 4인 팀, 프론트엔드 2명

- 문제: 로그인 상태, 학교 등록 여부, 선택한 학교 상태가 얽혀 있어 화면 진입 조건과 표시 정보가 계속 달라지는 구조
- 내 역할: 프론트엔드 2명 중 인증 흐름, 전역 상태, 메인 화면 구조를 맡아 구현. React Query로 서버 상태를, Zustand로 선택 상태를 분리하고 보호 라우팅과 XSRF 처리를 적용
- 결과: 로그인 여부와 학교 상태가 섞여 있던 화면 분기 기준을 분리해 수정 범위를 줄였고, 학교 검색에는 400ms 디바운스를 적용해 불필요한 조회를 줄였습니다.
- 기술: React, TypeScript, TanStack Query, Zustand, React Router, Vite, CSS Modules
- 링크: [저장소](https://github.com/sw-2-2/recall-frontend) | [데모](https://recallhub.vercel.app/login?redirect=%2F)

### AES Portfolio App
<p align="center">
  <img src="./assets/aes-portfolio-thumbnail.png" alt="AES Portfolio App projects section thumbnail" width="720" />
</p>

Markdown 문서와 화면 코드를 분리해 관리 비용을 낮춘 포트폴리오 웹앱

- 문제: 프로젝트와 경력 상세를 계속 추가해야 해서, 소개 문구를 직접 수정하는 방식으로는 관리가 번거로운 상황
- 내 역할: 프로젝트/경력 데이터 구조 설계, Markdown 상세 렌더링, 댓글 CRUD, Supabase 연동, 배포
- 결과: 상세 내용 수정은 화면 컴포넌트가 아니라 문서와 데이터 중심으로 반영할 수 있게 정리했고, 새 프로젝트를 추가하는 흐름도 단순화했습니다.
- 기술: React, TypeScript, Vite, React Router, TanStack Query, Supabase
- 링크: [저장소](https://github.com/wonis1/AES-portfolio-app) | [데모](https://aes-portfolio-app.vercel.app/#about)

---

### 강점

- 운영 중인 서비스에서 화면만 보지 않고 요청과 로그까지 함께 봅니다.
- 인증 상태, 서버 상태, 선택 상태를 섞지 않고 역할별로 분리합니다.
- 고객사 요구사항을 전달하는 데서 멈추지 않고, 구현 단위로 정리해 개발 조직과 조율합니다.

---

### 경력

### MindWareService | 솔루션 엔지니어
2023.03 - 2025.08

- 챗봇·콜봇 구축과 운영 과정에서 프론트 화면 수정, API 연동, 시나리오 변경, 장애 대응 수행
- 고객사 문의를 단순 접수하지 않고 원인 구간을 먼저 정리한 뒤 내부 개발 조직과 조율
- 우리카드, 코웨이, MindWareWorks 홈페이지 등에서 운영 이슈 대응, 연동 문서 작성, 고객사 교육 수행

---

### 기술 키워드

React, TypeScript, JavaScript, HTML, CSS, TanStack Query, Zustand, Supabase, REST API

---

### 학력 및 교육

- 선문대학교 산업경영공학과 | 공학사 | 2016.03 - 2023.02
- 현대오토에버 모빌리티 SW 스쿨 3기 | 웹앱 과정 | 2025.12 - 2026.06 수료 예정
