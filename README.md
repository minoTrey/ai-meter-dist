# AI Meter (Windows & Android)

GPT, Claude, Gemini(Antigravity 포함), Grok 사용량을 한눈에 확인하는 경량 데스크톱 · 모바일 위젯입니다.

## 다운로드

- **Windows 설치형 (`AIMeter-Setup.exe`)**: [최신 버전 다운로드](https://github.com/minoTrey/ai-meter-dist/releases/latest/download/AIMeter-Setup.exe)
- **Windows 무설치 압축판 (`AIMeter-Windows.zip`)**: [최신 버전 다운로드](https://github.com/minoTrey/ai-meter-dist/releases/latest/download/AIMeter-Windows.zip)
- **Android 앱 · 홈 화면 위젯 (`AIMeter-Android.apk`)**: [최신 버전 다운로드](https://github.com/minoTrey/ai-meter-dist/releases/latest/download/AIMeter-Android.apk)

## 설치 방법

### 다른 Windows PC에 설치하기
1. `AIMeter-Setup.exe`를 내려받아 실행하면 바탕화면 · 시작 메뉴 · 로그인 시 자동 실행이 설정됩니다.
2. 설치 후에는 새 버전이 출시될 때만 상단 **업데이트** 버튼이 활성화되며, 한 번의 클릭으로 자동 업데이트됩니다.
3. 무설치 포터블 실행을 원하면 `AIMeter-Windows.zip`을 압축 해제한 뒤 `AIMeter.exe`를 실행하세요. (`WebView2 Runtime`이 없는 PC는 Microsoft Edge WebView2 런타임 설치가 필요합니다.)

### Android 모바일 · 홈 화면 위젯 설치하기
1. 스마트폰에서 `AIMeter-Android.apk`를 내려받아 설치하세요. (최초 1회 "출처를 알 수 없는 앱 설치 허용" 필요)
2. 앱 하단 `+ GPT`, `+ Claude`, `+ Gemini`, `+ Grok` 버튼으로 직접 로그인해 사용량을 조회할 수 있습니다.
3. 앱 하단 **홈 위젯 추가** 또는 홈 화면 길게 누르기 -> **위젯 -> AI METER (`4x2` / `2x1`)**를 추가하세요.

### PC ↔ 모바일 동기화 (Antigravity 사용량 포함, 선택)
1. GitHub에서 **Secret (Private) Gist** 1개와 `gist` 권한만 가진 Personal Access Token을 생성합니다.
2. Windows AI Meter **설정 -> 모바일 동기화 (GitHub Gist)**에 Gist ID와 토큰을 입력합니다. (인증 토큰·쿠키를 제외한 사용량 요약 스냅샷만 업로드됩니다.)
3. Android AI Meter 상단 **PC 동기화**에 같은 Gist ID와 토큰을 입력하면 PC에서 수집한 Antigravity 및 AI 사용량이 모바일 앱과 위젯에 반영됩니다.