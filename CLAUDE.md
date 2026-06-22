# CLAUDE.md

이 저장소는 blue-wind.com 정적 사이트(GitHub Pages, CNAME)이며, 앱별 법적 문서
(개인정보처리방침·이용약관) 등 HTML 페이지를 게시한다.

## 세션 공통 메모리
- 세션 시작 시 `memory/` 디렉터리를 확인할 것. 세션 간 이어갈 맥락·공유 노트가 들어 있다.
- Slack 공유용 요약은 `memory/slack/`에 `YYYY-MM-DD-<주제>.md`로 누적한다.

## 작업 규칙
- 변경은 feature 브랜치에서 → PR → (승인 후) main 머지.
- 법적 문서를 "실질 변경"하면 문서 시행일을 올리고, 해당 앱 저장소의 동의 버전 상수와
  날짜를 일치시킨다. (예: 36.5도/baby_temp_voice_app 의 `LegalVersions`)
