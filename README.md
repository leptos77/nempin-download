# Inkling 내려받기

말하면 받아쓰고, 잘못 들린 말을 맥락으로 고치고, AI에게 넣기 좋은 글로 정리해 지금 쓰는 앱에 붙여 넣는 메뉴 막대 앱이다. 소개: https://inkling.ilsoft.net

설치 파일은 [Releases](https://github.com/leptos77/inkling-download/releases)에만 있다. 이 저장소에는 코드가 없다.

## 항상 최신판 주소

| | 주소 |
|---|---|
| 맥 (Apple 칩, macOS 15 이상) | `https://github.com/leptos77/inkling-download/releases/latest/download/Inkling-mac.dmg` |
| 윈도우 | 준비 중 (나오면 `…/releases/latest/download/Inkling-windows-setup.exe`) |

## 설치

- 맥: `Inkling-mac.dmg`를 열고 `Inkling`을 `Applications`로 끌어다 놓는다. 인텔 Mac은 아직 안 된다.
- 처음 켜면 "시작하기" 창이 뜬다.
  1. 받아쓰기 모델(547MB)을 한 번 받는다. 모델은 [ilsoft-models](https://github.com/leptos77/ilsoft-models)에 있다.
  2. Gemini API 키를 넣는다. 키는 https://aistudio.google.com/apikey 에서 무료로 받는다. 무료 키는 보낸 글이 Google의 제품 개선에 쓰일 수 있다.
  3. 마이크와 손쉬운 사용 권한을 허용한다.
- 그다음 `⌃⇧Space`를 누른 채 말한다.

## 처음 열 때

지인 배포용이라 Apple·Microsoft 서명을 받지 않았다. 처음 한 번 경고가 뜬다.

- 맥: 앱을 열면 "열 수 없음"이 뜬다 → 시스템 설정 → 개인정보 보호 및 보안 → 아래쪽 "그래도 열기".
- 윈도우: (준비 중) "Windows의 PC 보호"가 뜨면 → "추가 정보" → "실행".

## 새 판으로 바꾸기

같은 주소에서 다시 받아 `Applications`의 Inkling을 덮어쓴다. 받은 모델과 설정은 그대로 남는다.
