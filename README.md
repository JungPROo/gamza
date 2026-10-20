# 🥔 감자 마켓 (Gamza Market)

> **포슬포슬 따뜻한 이웃 간 중고거래 플랫폼**

Supabase 백엔드와 연동되어 동작하는 이웃 기반 중고 직거래 웹 애플리케이션입니다.

## ✨ 주요 기능

- 📋 **물품 목록 조회 (`index.html`, `screen1_list.html`)**
  - 동네 기반 중고 거래 물품 탐색
  - 카테고리별 필터 및 검색 기능
- 🔍 **상세 페이지 (`screen2_detail.html`)**
  - 거래 물품 상세 정보, 판매자 정보, 매너 온도 확인
  - 관심 상품 찜하기 및 채팅하기
- ✍️ **판매 글 등록 (`screen3_write.html`)**
  - 사진 업로드, 제목/카테고리/가격 입력, 거래 희망 장소 설정
- 💬 **실시간 채팅 (`screen4_chat.html`)**
  - 구매자-판매자 간 실시간 1:1 대화 및 거래 조율

## 🛠️ 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla JS)
- **Backend / DB**: Supabase (Database, Auth, Realtime)

## 🚀 시작하기

### 1. 환경 설정
Supabase 프로젝트 설정 후 연동 정보를 설정합니다.
`.env.example`을 참고하여 환경변수를 구성할 수 있습니다.

```env
SUPABASE_URL=your_supabase_project_url
SUPABASE_ANON_KEY=your_supabase_anon_key
```

### 2. 실행
정적 웹 서버(Live Server 등) 또는 웹 브라우저를 통해 `index.html`을 엽니다.
