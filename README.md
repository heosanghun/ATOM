# ATOM DYNAMICS — Sovereign O(1) Constant Memory Infrastructure

차세대 소버린 AI 플랫폼 **ATOM DYNAMICS (Cogni-OS™ Sovereign AI Platform)** 공식 홈페이지 워크스페이스입니다.

## 📁 프로젝트 구조

```text
HOMEPAGE/
├── index.html              # 메인 랜딩 페이지 (ATOM DYNAMICS)
├── DESIGN.md               # 디자인 시스템 토큰 명세서
├── package.json            # 로컬 프리뷰 및 실행 스크립트
├── .env                    # STITCH_API_KEY 환경 설정
├── .agents/
│   └── mcp_config.json     # 워크스페이스 MCP 서버 설정
├── assets/
│   └── images/             # 하드웨어 노드, AR 스마트글라스, 실증 현장 고화질 이미지
└── screens/
    ├── physical_ai_data_factory.html # Physical AI Data Factory 상세 화면
    └── equis_axis_ai_logo.html       # 로고 시스템
```

## 🚀 로컬 미리보기 실행

```bash
npm run dev
# 또는
npx -y serve .
```
브라우저에서 `http://localhost:3000`으로 접속하여 사이트를 확인할 수 있습니다.

## 🔌 Stitch MCP 연동

이 프로젝트는 Google Stitch MCP 서버와 연동되어 대화창에서 바로 UI 화면 생성, 수정, 디자인 시스템 동기화를 수행할 수 있습니다.
