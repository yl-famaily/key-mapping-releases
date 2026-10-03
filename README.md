# 키 매핑 (KeyMapping)

Windows용 키보드 리매핑 앱입니다. 연결된 키보드를 인식해 배열을 보여주고, 키를 클릭해서 동작을 바꿀 수 있습니다.

## 다운로드

[Releases](../../releases/latest)에서 받으세요.

- `KeyMapping-Setup-x.y.z.exe` — 설치 버전 (시작 메뉴·바탕화면 바로가기 생성)
- `KeyMapping-x.y.z-portable.exe` — 설치 없이 바로 실행

> 코드 서명이 없어서 처음 실행할 때 Windows SmartScreen 경고가 나올 수 있습니다. **추가 정보 → 실행**을 누르세요.

## 기능

- **다른 키로** 바꾸기 (예: CapsLock → Ctrl)
- **단축키 조합** 입력 (예: F1 → Ctrl+C)
- **사용 안 함** — 키를 눌러도 반응하지 않게
- **키보드 배열 자동 인식**
  - QMK 키보드 3,200여 종의 배열 내장, USB ID가 일치하면 자동 선택
  - 내장 배열: 한국어 106 / US 104 / TKL / ThinkPad P1 Gen 7 / 노트북 / Apple Magic Keyboard
  - 배열 이름·제조사로 직접 검색 가능
- 어떤 키인지 모르는 칸은 클릭 후 실제 키를 눌러 지정
- 창을 닫으면 트레이에서 계속 동작, 트레이 메뉴 **종료** 시 모든 키 원상 복구
- **비상 해제**: `Ctrl + Alt + Shift + Esc` — 모든 매핑을 즉시 끄거나 켭니다

## 제약

- 매핑은 앱이 실행 중일 때만 적용됩니다.
- 관리자 권한으로 실행된 프로그램에는 적용되지 않습니다 (필요하면 이 앱도 관리자 권한으로 실행).
- `Ctrl+Alt+Del`, 키보드 내부에서 처리되는 `Fn` 키는 바꿀 수 없습니다.
- Windows 10/11 64비트 전용입니다.

키보드 배열 데이터: [QMK Firmware](https://github.com/qmk/qmk_firmware) (GPL-2.0)
