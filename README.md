# tubekeeper-releases

**공식 홈페이지: https://matdori.shop**

TubeKeeper 릴리즈 배포용 저장소입니다.

## 다운로드 / 설치

👉 **[최신 버전 다운로드](https://github.com/SongJongwon/tubekeeper-releases/releases/latest)**

위 링크에서 본인 OS에 맞는 파일을 받으세요.

- **Windows**: `TubeKeeper-Setup-x.x.x.exe` — 더블클릭 설치. 이후 자동 업데이트됩니다.
- **macOS (M칩)**: `...-arm64.dmg` / **macOS (인텔)**: `...x.x.x.dmg`
  첫 실행 시 앱 우클릭 → "열기"로 실행하세요. (자동 업데이트 미지원, 새 버전은 직접 받아 설치)
- **Linux**: `...x.x.x.AppImage` (실행 권한 부여 후 실행) 또는 `...amd64.deb` (`sudo dpkg -i`로 설치)

자세한 안내는 공식 홈페이지에서 볼 수 있습니다: https://matdori.shop

■ TubeKeeper 설치 안내

────────────────────────────
🪟 Windows 사용자
────────────────────────────
다운로드: TubeKeeper-Setup-0.2.0.exe

설치 방법
1. 위 .exe 파일을 다운로드하세요.
2. 다운로드한 파일을 더블클릭하면 설치가 시작됩니다.
3. 설치 후 바로 실행하면 됩니다.

💡 설치 중 파란색 "Windows의 PC 보호" 경고가 뜨면,
   "추가 정보" → "실행"을 누르세요.
   (아직 코드 서명 전이라 뜨는 정상적인 안내입니다.)
✅ 한 번 설치하면 이후 새 버전은 자동으로 업데이트됩니다.


────────────────────────────
🍎 macOS 사용자
────────────────────────────
다운로드: 본인 Mac에 맞는 파일을 받으세요.
- Apple Silicon (M1/M2/M3/M4 등 최신 Mac): TubeKeeper-0.2.0-arm64.dmg
- Intel Mac (2020년 이전 구형):            TubeKeeper-0.2.0.dmg

※ 내 Mac이 뭔지 모르겠다면:
  화면 왼쪽 위 사과(🍎) 메뉴 → "이 Mac에 관하여"에서 칩(Chip) 항목 확인.
  "Apple M..."이면 arm64, "Intel"이면 일반 dmg.

설치 방법
1. dmg 파일을 받아 더블클릭한 뒤, TubeKeeper 아이콘을
   응용 프로그램(Applications) 폴더로 드래그하세요.
2. 첫 실행 때 주의: 그냥 더블클릭하면 "확인되지 않은 개발자"
   경고가 뜨며 안 열립니다. 이때는 앱 아이콘을
   마우스 우클릭(또는 Control+클릭) → "열기"를 누르고,
   다시 뜨는 창에서 한 번 더 "열기"를 누르세요.
3. 한 번만 이렇게 열면, 그다음부터는 평소처럼 더블클릭으로 실행됩니다.

⚠️ 이 경고는 바이러스가 아니라, 아직 Apple 코드 서명을
   받지 않아서 뜨는 안내입니다.
⚠️ macOS는 자동 업데이트가 되지 않습니다.
   새 버전이 나오면 앱 안에서 업데이트되지 않으니,
   이 웹사이트에 다시 오셔서 최신 dmg를 직접 내려받아
   기존 앱 위에 다시 설치해 주세요.


────────────────────────────
🐧 Linux 사용자
────────────────────────────
다운로드: 둘 중 편한 방식 하나를 고르세요.
- AppImage (거의 모든 배포판에서 작동, 추천): TubeKeeper-0.2.0.AppImage
- deb (Ubuntu / Debian 계열):                tubekeeper_0.2.0_amd64.deb

AppImage 설치 방법
1. .AppImage 파일을 다운로드하세요.
2. 파일에 실행 권한을 주세요.
   (파일 우클릭 → 속성 → "실행 가능" 체크,
    또는 터미널에서: chmod +x TubeKeeper-0.2.0.AppImage)
3. 더블클릭하면 설치 없이 바로 실행됩니다.

deb 설치 방법 (Ubuntu/Debian)
1. .deb 파일을 다운로드하세요.
2. 더블클릭해서 소프트웨어 설치 관리자로 설치하거나,
   터미널에서: sudo dpkg -i tubekeeper_0.2.0_amd64.deb
