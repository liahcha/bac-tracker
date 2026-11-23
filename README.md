# BAC Tracker

블랙야크 알파인 클럽(BAC) 공식 정규 20개 챌린지(812개 고유 인증지 · 847개 인증 항목)를 PC와 모바일에서 통합 관리하고, 구글 드라이브 스프레드시트(`BAC인증_Master`)와 실시간 자동 동기화하는 PWA 웹앱입니다.

## 포함된 파일 구성
- `index.html`: PC뷰 / 모바일뷰 통합 메인 웹앱 (구글 시트 실시간 양방향 자동 연동 내장)
- `manifest.json`: iOS / Android 홈 화면 추가(PWA) 매니페스트
- `sw.js`: PWA 설치 및 빠른 로딩을 위한 서비스 워커
- `icon-512.png`, `icon-192.png`, `apple-touch-icon.png`, `favicon.png`: 전용 앱 아이콘 세트
- `.nojekyll`: GitHub Pages 정적 배포 설정 파일

## GitHub Pages 배포 방법
1. 이 폴더의 모든 파일을 GitHub Public 저장소 최상위(root)에 업로드합니다.
2. 저장소의 **Settings → Pages → Branch: `main` / `/ (root)` → Save**를 클릭합니다.
3. 발급된 HTTPS 주소로 접속해 PC·모바일 어디서나 인증 체크 시 구글 시트에 자동 반영됩니다.
