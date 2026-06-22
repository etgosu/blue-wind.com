# CLAUDE.md

이 저장소는 blue-wind.com 정적 사이트(GitHub Pages, CNAME)이며, 앱별 법적 문서
(개인정보처리방침·이용약관) 등 HTML 페이지를 게시한다.

## 세션 공통 메모리
- **새 앱(또는 기존 앱)의 개인정보처리방침·이용약관을 만들거나 고치기 전에는
  반드시 `memory/app-legal-launch-lessons.md` 를 먼저 읽는다.** 과거 시행착오
  (로그인 강제 출시 → App Store 거절 → 게스트 모드 재작업)를 반복하지 않기 위한
  체크리스트가 들어 있다.
- `memory/`에는 세션 간 이어갈 **지속 사실·규칙만** 둔다.
- 특정 작업의 Slack 공유 요약 등 **일회성 산출물은 `docs/slack/`** 에
  `YYYY-MM-DD-<주제>.md`로 보관한다.

## 작업 규칙
- 변경은 feature 브랜치에서 → PR → (승인 후) main 머지.
- 법적 문서를 "실질 변경"하면 문서 시행일을 올리고, 해당 앱 저장소의 동의 버전 상수와
  날짜를 일치시킨다. (예: 36.5도/baby_temp_voice_app 의 `LegalVersions`)
