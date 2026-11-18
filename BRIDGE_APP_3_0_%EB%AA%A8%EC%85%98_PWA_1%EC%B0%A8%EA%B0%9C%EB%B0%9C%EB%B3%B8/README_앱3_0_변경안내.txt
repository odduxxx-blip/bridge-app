BRIDGE APP 3.0 — 모션/PWA 초기 개발본

기반: 기존 BRIDGE 2.2 ZIP. 원본 2.2는 변경되지 않았습니다.
변경: 화면 진입/카드/버튼/모달의 부드러운 2D 트랜지션, 터치 반응, 저감 모션 접근성, 홈 화면 설치용 manifest/icons, 오프라인 데모 캐시용 service worker.
유지: 기존 3역할, 모든 HTML/JS 데이터·예약·수락·후기·가격·시연 정책, 원래 로고/이미지 자산.
주의: Google 로그인, 서버 DB/관리자 동기화, 결제, 실푸시는 구현되지 않았습니다. 기존 admin.html도 구형 정책을 담은 상태이므로 이 단계에서는 독립 데모만으로 사용하세요.
배포: index.html, admin.html, assets/, icons/, manifest.webmanifest, sw.js 를 동일한 HTTPS 호스팅 루트로 업로드. Cloudflare Pages 등에서 HTTPS로 열어야 PWA 서비스 워커가 동작합니다. file:// 더블클릭으로는 PWA 설치 테스트 불가.
안전: 원본 발표용 BRIDGE 2.2 배포 사이트를 덮어쓰지 말고 별도 미리보기 주소에 게시. 이 ZIP은 앱 전환 제1차 결과물입니다.
