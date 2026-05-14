<div align="center">
  <img src="assets/icon.png" width="120" alt="PuppyWidget">

  # PuppyWidget

  반려동물 용품/일정/메모를 한 곳에서 관리하는 Windows 데스크톱 위젯

  ![platform](https://img.shields.io/badge/platform-Windows-blue)
  ![license](https://img.shields.io/badge/license-Freeware-green)
  [![release](https://img.shields.io/github/v/release/TaeheeLim/puppy-widget?color=ff8fab)](https://github.com/TaeheeLim/puppy-widget/releases/latest)
  [![downloads](https://img.shields.io/github/downloads/TaeheeLim/puppy-widget/total?color=ff8fab)](https://github.com/TaeheeLim/puppy-widget/releases)
</div>

---

## 다운로드

### ▶ [최신 버전 받기](https://github.com/TaeheeLim/puppy-widget/releases/latest)

| 파일 | 설명 |
|---|---|
| `PuppyWidget-x.x.x-Setup.exe` | 정식 설치 (시작 메뉴/바탕화면 바로가기 자동 생성) |
| `PuppyWidget-x.x.x-portable.exe` | 설치 없이 실행 (USB 등에 들고 다닐 때) |

> **처음 실행하면 "Windows에서 PC를 보호했습니다" 경고가 뜹니다.**
> "추가 정보 → 실행"을 누르시면 설치가 진행됩니다. 코드 서명 인증서가 없어서 뜨는 경고이며 안전한 앱입니다.

## 어떤 앱인가요?

강아지/고양이 같은 반려동물 키우시는 분들을 위한 작은 데스크톱 위젯입니다. 사료가 얼마나 남았는지, 다음 병원 예약이 언제인지, 오늘 산책은 다녀왔는지 — 이런 사소하지만 자꾸 까먹게 되는 것들을 화면 구석에 띄워두고 한눈에 보세요.

처음에는 강아지용으로 만들었는데, 위젯 제목과 아이콘을 자유롭게 바꿀 수 있어서 고양이, 토끼, 햄스터 등 어떤 반려동물이든 쓰실 수 있습니다.

## 주요 기능

- **용품 관리** — 사료, 패드, 간식 등 용품 잔량(%) 추적, 떨어지면 구매 링크로 바로 이동
- **자동 잔량 계산** — 구매일과 예상 소진일을 입력하면 매일 자동으로 잔량 % 갱신
- **요일별 메모** — 월~일 요일마다 일기/메모 저장
- **일정 관리 + 알림** — 산책, 병원, 미용, 예방접종, 개인 일정 등록 후 Windows 토스트 알림
- **월간 캘린더 뷰** — 어느 날 어떤 일정이 있는지 한눈에
- **드래그앤드롭** — 항목 순서를 자유롭게 정렬
- **위젯 커스터마이징** — 이모지와 제목을 반려동물에 맞게 변경
- **항상 위에 표시 + 자동 실행** — 데스크톱에 고정해두고 부팅 시 자동 실행

## 스크린샷

> 추후 업데이트 예정

<!--
스크린샷 추가 예시:
<p align="center">
  <img src="screenshots/main.png" width="300" alt="메인 화면">
  <img src="screenshots/calendar.png" width="300" alt="캘린더 뷰">
</p>
-->

## 사용법

### 처음 실행하면
1. 우측 상단의 ⚙ 설정 버튼을 눌러 **반려동물 이름**과 **이모지**를 변경하세요
2. 위젯이 항상 위에 떠 있고, Windows 시작 시 자동 실행됩니다 (트레이 메뉴에서 끌 수 있음)

### 용품 등록
- "+추가" 버튼으로 사료, 패드, 간식 등 등록
- **구매일과 예상 소진일을 입력하면** 잔량 %가 매일 자동으로 줄어듭니다
- 구매 링크를 등록해두면 떨어졌을 때 "🛒 구매" 버튼으로 바로 이동

### 일정 알림
- 일정 추가 시 알림 시간을 선택 (5분/10분/30분/1시간/3시간/1일 전 등)
- 시간이 되면 Windows 알림으로 알려드립니다
- 알림이 안 뜨면 → [자주 묻는 질문](#자주-묻는-질문) 참고

### 캘린더 보기
- 일정 탭 우측의 📅 버튼으로 월간 캘린더 뷰 전환
- 날짜 클릭 시 그 날의 일정 표시 + 빠른 추가

## 자주 묻는 질문

<details>
<summary><b>설치할 때 "Windows에서 PC를 보호했습니다" 경고가 떠요</b></summary>

코드 서명 인증서를 등록하지 않아서 뜨는 경고입니다. **추가 정보 → 실행** 을 누르시면 정상적으로 설치됩니다. 인증서는 연 $300 정도로 비싸서 사용자가 늘어나면 그때 등록할 예정이에요.

</details>

<details>
<summary><b>일정 알림이 안 떠요</b></summary>

다음을 차례대로 확인해주세요.

1. **설정 → 🔔 알림 테스트 버튼**을 눌러보세요. 여기서 알림이 안 뜨면 Windows 알림 권한 문제입니다.
2. Windows 설정 → 시스템 → 알림에서 **PuppyWidget** 항목이 켜져 있는지 확인
3. **포커스 어시스트(방해 금지 모드)** 가 켜져있으면 알림이 표시되지 않으니 끄세요
4. v1.2.1 이전 버전에서 알림이 안 뜨던 버그가 있었습니다. 최신 버전으로 업데이트해주세요.

</details>

<details>
<summary><b>데이터는 어디에 저장되나요?</b></summary>

`%APPDATA%\puppy-widget\config.json` 파일에 저장됩니다.
Win + R을 누른 뒤 `%APPDATA%\puppy-widget` 을 입력하면 폴더가 열립니다.
다른 PC로 옮길 때는 이 파일만 복사하시면 돼요.

</details>

<details>
<summary><b>강아지가 아니라 고양이/토끼 키우는데도 쓸 수 있나요?</b></summary>

네, 위젯 제목과 이모지를 자유롭게 바꿀 수 있습니다. 우측 상단의 ⚙ 버튼을 누르고 이모지(🐱 🐰 🐹 🐦 🐢 등) 선택, 제목을 "냥냥이" 같은 걸로 바꾸면 됩니다.

</details>

<details>
<summary><b>위젯을 화면에서 안 보이게 하려면?</b></summary>

타이틀바의 × 버튼이나 ─ 버튼을 누르면 **트레이로 숨겨집니다** (종료 아님). 다시 보려면 작업 표시줄 트레이 영역의 🐶 아이콘을 클릭하세요.
완전히 종료하려면 트레이 아이콘 우클릭 → 종료입니다.

</details>

<details>
<summary><b>업데이트는 어떻게 받나요?</b></summary>

현재는 자동 업데이트 기능이 없습니다. 새 버전이 나오면 [Releases 페이지](https://github.com/TaeheeLim/puppy-widget/releases/latest)에서 최신 Setup.exe를 다운로드 → 실행하시면 기존 데이터는 유지하면서 업데이트됩니다.

</details>

<details>
<summary><b>소스 코드도 공개되어 있나요?</b></summary>

소스 코드는 비공개입니다. 다운로드 파일 자체는 자유롭게 사용/배포하셔도 됩니다.

</details>

## 변경 이력

| 버전 | 날짜 | 주요 변경사항 |
|---|---|---|
| v1.2.1 | 2026-05-14 | 일정 알림 안 가던 버그 수정 |
| v1.2.0 | 2026-05-14 | 캘린더 뷰, 자동 잔량 계산, 개인 일정, flatpickr 도입 |
| v1.1.0 | 2026-05-14 | 위젯 커스터마이징, 드래그앤드롭, 일정 알림 |
| v1.0.0 | 2026-05-14 | 첫 릴리스 |

자세한 내용은 [Releases](https://github.com/TaeheeLim/puppy-widget/releases)를 참고하세요.

## 버그 제보 / 기능 제안

[Issues 페이지](https://github.com/TaeheeLim/puppy-widget/issues)에 남겨주시면 확인 후 반영하겠습니다.

## 라이선스

배포 파일은 개인 사용 및 비상업적 용도로 자유롭게 사용하실 수 있습니다.
