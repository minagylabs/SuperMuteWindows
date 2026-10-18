<p align="right">
  <b>한국어</b> | <a href="README_en.md">English</a> | <a href="README_jap.md">日本語</a> | <a href="README_zh.md">中文</a>
</p>

# Super Mute (Windows) — 슈퍼무음 윈도우

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo/minagy_monogram_coral.png">
    <source media="(prefers-color-scheme: light)" srcset="logo/minagy_monogram.png">
    <img src="logo/minagy_monogram.png" alt="Minagy Labs Logo" width="140" height="140" />
  </picture>
</p>

<p align="center">
  <b>삼성 갤럭시 카메라 셔터음 1초 무음 설정 윈도우 포터블 유틸리티</b><br>
  Built by <b>Minagy Labs</b>
</p>

<p align="center">
  <a href="https://github.com/minagylabs/SuperMuteWindows"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fminagylabs%2FSuperMuteWindows&count_bg=%23238636&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Visitors&edge_flat=true" alt="Visitors"></a>
  <a href="https://github.com/minagylabs/SuperMuteWindows/releases/latest"><img src="https://img.shields.io/badge/Release-v1.0.0-238636.svg?style=flat-square" alt="Release"></a>
  <a href="https://github.com/minagylabs/SuperMuteWindows/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square" alt="License"></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(x64)-0078D6.svg?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/Binary-Portable%20EXE%20(No%20Install)-informational.svg?style=flat-square" alt="Binary">
  <img src="https://img.shields.io/badge/Samsung%20Knox-0x0%20(Safe%20%26%20Untripped)-success.svg?style=flat-square" alt="Knox Safe">
  <img src="https://img.shields.io/badge/Security-100%25%20Offline%20%2F%20Zero%20Data-9cf.svg?style=flat-square" alt="Security">
  <a href="https://buymeacoffee.com/minagylabs"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support-yellow.svg?style=flat-square" alt="Buy Me a Coffee"></a>
  <a href="https://www.instagram.com/minagylabs/"><img src="https://img.shields.io/badge/Instagram-@minagylabs-E4405F.svg?style=flat-square" alt="Instagram"></a>
</p>

<p align="center">
  <img src="logo/supermute_main_ko.png" alt="Super Mute (Windows) Main Window" width="500" />
  &nbsp;&nbsp;
  <img src="logo/supermute_drawer_ko.png" alt="Super Mute Quick Guide Drawer" width="500" />
</p>

---

## 소개

**Super Mute (Windows)**는 한국 및 일본 규제(TTA 표준)로 인해 강제 적용된 삼성 갤럭시 스마트폰의 카메라 셔터음을 안전하게 무음화하는 윈도우 포터블 유틸리티입니다.

* **순정 카메라 원본 화질 유지**: 화면 캡처 방식의 저화질 무음 카메라 앱과 달리, 삼성 순정 카메라의 원본 센서 화질, 야간 모드, 광학 줌, HDR을 그대로 지원합니다.
* **안드로이드 전 버전 호환**: 안드로이드 14 이후 보안 정책 강화로 차단된 기존 앱(SetEdit 등)과 달리, 최신 안드로이드 16(One UI 8.5) 및 차세대 One UI 9까지 OS 버전에 구애받지 않고 구형부터 최신 갤럭시 기종까지 정상 동작합니다.
* **녹스(Knox) 워런티 무손상 (`0x0`)**: 루팅이나 펌웨어 개조가 전혀 필요 없어 녹스 카운터가 깨지지 않으며 삼성페이, 삼성패스, 보안폴더, 금융 앱이 정상 작동합니다.
* **진동/무음 모드 연동**: 소리 모드에서는 정상 셔터음이 울리고, **진동 또는 무음 모드일 때만 셔터음이 무음**으로 전환됩니다.

---

## 다운로드

| 파일명 | 지원 OS | 파일 크기 | 형태 | 다운로드 |
| :--- | :--- | :---: | :---: | :--- |
| **`SuperMute.exe`** | Windows 10 / 11 (64-bit) | ~55 MB | 단일 무설치 포터블 | [**최신 릴리즈 다운로드**](https://github.com/minagylabs/SuperMuteWindows/releases/latest) |

> **무설치 단일 파일**: 별도의 설치 과정 없이 다운로드 후 바로 실행할 수 있는 단일 포터블 파일이며, 전용 폰트와 통신 모듈이 자체 내장되어 있어 PC 레지스트리에 잔여물을 남기지 않습니다.

---

## 보안 및 10초 안전 수칙

사용자의 기기 보안과 개인정보 보호를 위한 안전 수칙입니다:

1. **PC 사전 바이러스 검사**:
   - 휴대폰을 연결하기 전 Windows Defender 또는 백신 프로그램으로 PC를 검사하여주세요.
2. **1-클릭 실행**:
   - USB 케이블로 휴대폰을 연결하고 화면의 디버깅 권한을 허용한 후 **'소리 끄기'** 버튼을 클릭합니다.
3. **10초 안전 수칙 준수**:
   * 상태 창에 `카메라 셔터음: 무음 (0) ✓`이 표시되면 즉시 USB 케이블을 분리합니다.
   * 휴대폰 **설정 → 개발자 옵션**에서 **'USB 디버깅'을 즉시 끕니다.**
4. **최소 권한 보장**:
   * 본 프로그램은 카메라 셔터음 관련 시스템 설정값 딱 1개만 안전하게 조회하고 수정합니다.
   * 휴대폰에 불필요한 앱(APK), 백그라운드 데몬, 또는 수정된 시스템 파일을 절대 설치하지 않으며, 프로그램 종료 시 열려 있는 통신 세션을 즉시 안전하게 종료합니다.

---

## 사용 방법

1. 휴대폰의 **설정 → 개발자 옵션**에서 **'USB 디버깅'**을 켭니다.  
   *(개발자 옵션이 보이지 않는 경우: **설정 → 휴대전화 정보 → 소프트웨어 정보**에서 **'빌드번호'**를 연속 7회 터치하세요).*
2. USB 케이블로 휴대폰을 PC에 연결합니다.
3. 휴대폰 화면에 **'USB 디버깅을 허용하시겠습니까?'** 창이 나타나면 **'허용'**을 누릅니다.
4. PC에서 `SuperMute.exe`를 실행하고, **'소리 끄기'** 버튼이 흰색으로 활성화되면 클릭합니다.
5. 상태 카드가 `카메라 셔터음: 무음 (0) ✓`으로 변경되었는지 확인합니다.
6. USB 케이블을 분리하고 휴대폰 설정에서 **'USB 디버깅'을 즉시 끕니다.**

---

## 지원 기기

| 기기 시리즈 | 대상 OS | 지원 여부 | 적용 후 동작 |
| :--- | :--- | :---: | :--- |
| **Galaxy S 시리즈**<br>(S7 ~ S24 / S25 / S26) | One UI 1.0 ~ 8.5 / 9+<br>(Android 7 ~ 16+) | **지원 ✓** | 휴대폰이 진동 또는 무음 모드일 때 순정 카메라 무음 |
| **Galaxy Z 시리즈**<br>(Fold 1~8, Flip 1~8) | One UI 1.1 ~ 8.5 / 9+<br>(Android 9 ~ 16+) | **지원 ✓** | 커버 및 내부 메인 카메라 모두 무음 적용 |
| **Galaxy Note 시리즈**<br>(Note 8 ~ Note 20 Ultra) | One UI 1.0 ~ 4.1<br>(Android 7 ~ 12) | **지원 ✓** | 진동 또는 무음 모드일 때 무음 동작 |
| **Galaxy A / M / Quantum 시리즈**<br>(A10 ~ A55, M, 점프, 버디 등) | One UI / One UI Core<br>(Android 7 ~ 16+) | **지원 ✓** | 진동 또는 무음 모드일 때 무음 동작 |
| **Google Pixel / Xiaomi / iPhone** | 타사 제조사 OS | 지원 불가 | 삼성 순정 설정 방식을 사용하지 않으므로 지원하지 않습니다. |

---

## 자주 묻는 질문 (FAQ)

<details>
<summary><b>Q: 최신 안드로이드 16 및 One UI 8.5 / 9에서도 동작하나요? (타사 방식과의 차이점)</b></summary>
<br>
<b>네, 안드로이드 및 One UI 버전에 구애받지 않고 모든 갤럭시 기기를 지원합니다.</b><br>
기존의 온디바이스 설정 변경 앱(SetEdit 등)이나 과거 방식의 무음 도구들은 안드로이드 14 이상에서 보안 정책 강화로 권한이 원천 차단되어 작동이 불가능해졌습니다. 반면 <b>Super Mute (Windows)</b>는 이러한 OS 내부 권한 차단의 영향을 받지 않으므로, 안드로이드 7.0(누가) 구형 기종부터 최신 안드로이드 16(One UI 8.5) 및 차세대 One UI 9 탑재 플래그십 기종까지 정상 동작합니다.
</details>

<details>
<summary><b>Q: 스마트폰을 재부팅할 때마다 다시 연결해야 하나요?</b></summary>
<br>
<b>아닙니다.</b> 일상적인 재부팅이나 배터리 방전 후 켜져도 무음 설정은 영구 유지됩니다. 오직 연 1회 진행되는 대규모 안드로이드 판올림 업데이트(예: One UI 8.5 → One UI 9)나 공장초기화를 진행했을 때만 1회 다시 연결해주시면 됩니다.
</details>

<details>
<summary><b>Q: 케이블을 연결했는데 "기기 대기 중..."에서 넘어가지 않아요.</b></summary>
<br>
다음 사항을 확인해 주세요:
1. 사용 중인 USB 케이블이 단순 충전 전용이 아닌 <b>데이터 전송 지원 케이블</b>인지 확인합니다.
2. 스마트폰 <b>개발자 옵션</b>에서 <b>USB 디버깅</b>이 켜져 있는지 확인합니다.
3. 휴대폰 화면을 켜고 <b>'USB 디버깅을 허용하시겠습니까?'</b> 팝업창에서 <b>'허용'</b>을 누릅니다.
4. PC에 삼성 통합 USB 드라이버가 설치되어 있지 않은 경우, 삼성 Smart Switch를 설치하거나 삼성전자 공식 USB 드라이버를 설치하세요.
</details>

<details>
<summary><b>Q: 윈도우 스마트스크린이나 백신 프로그램에서 경고가 왜 뜨나요?</b></summary>
<br>
<code>SuperMute.exe</code>는 무료 오픈소스 환경에서 빌드된 독립 실행 파일(.exe)로, USB 기기 통신 모듈을 자체 포함하고 있습니다. 수백만 원에 달하는 고가의 상업용 기업 인증서(EV Code Signing)를 등록하지 않은 무료 오픈소스 유틸리티 특성상, 신규 릴리즈 직후에는 윈도우 평판 필터에 의해 경고가 표시될 수 있습니다. 악성 코드는 일체 포함되어 있지 않으므로 안심하고 사용하셔도 됩니다.
</details>

---

## 개발자 후원

Super Mute (Windows)는 **Minagy Labs**에서 무료로 배포하는 오픈소스 도구입니다. 광고나 유료 결제 없이 운영되고 있습니다.

본 프로그램이 일상과 업무에 도움이 되었다면 개발팀을 응원해 주세요:

<p align="center">
  <a href="https://buymeacoffee.com/minagylabs" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" width="200" />
  </a>
</p>

* **크티 (CTEE)**: [ctee.kr/place/minagy](https://ctee.kr/place/minagy)
* **Buy Me a Coffee**: [buymeacoffee.com/minagylabs](https://buymeacoffee.com/minagylabs)
* **Instagram**: [@minagylabs](https://www.instagram.com/minagylabs/)
* **GitHub Issues**: [minagylabs/SuperMuteWindows/issues](https://github.com/minagylabs/SuperMuteWindows/issues)
* **Email**: `minagylabs@gmail.com`

---

## 라이선스 및 크레딧

* **Software**: Released under the [MIT License](LICENSE).
* **Copyright**: Copyright © 2026 **Minagy Labs**. All rights reserved.
