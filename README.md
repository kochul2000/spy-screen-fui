# Spy Screen FUI

가상의 첩보기관 감시 화면을 구현한 FUI(Fantasy User Interface) 프로젝트입니다.

A fictional intelligence agency surveillance screen built as a FUI (Fantasy User Interface).

아이나 조카에게 보여주면 스파이 놀이하기 딱 좋습니다.
Great for playing spy with kids and nephews.

## Demo

**https://kochul2000.github.io/spy-screen-fui/**

## Features / 주요 기능

- **Global Tracking Map** — 요원 위치를 실시간 추적하는 세계 지도 / Real-time agent tracking on a world map
- **Satellite Orbits** — 위성 궤도 표시 및 주기적 위치 갱신 / Satellite ground tracks with periodic position updates
- **Agent Roster** — 현장 요원 목록 및 상태 표시 / Field agent list and status display
- **Surveillance Feed** — 감시 카메라 화면 시뮬레이션 / Simulated surveillance camera feeds
- **Signal Intelligence** — 신호 정보 분석 파형 / Signal intelligence waveform analysis
- **Comms Log** — 암호화된 통신 로그 / Encrypted communications log
- **Target Dossier** — 대상 프로필 및 위협 등급 / Target profile and threat level
- **Slash Commands** — `/auto`, `/sound`, `/comms`, `/event`, `/name` 등 인터랙티브 명령어 / Interactive slash commands

## Quick Start / 시작하기

`index.html` 파일 하나로 독립적으로 동작합니다. 빌드 도구나 외부 의존성이 필요 없습니다.
브라우저에서 파일을 열기만 하면 됩니다.

This project is a single `index.html` file that runs independently. No build tools, no dependencies.
Just open the file in a browser.

```
# 방법 1: 파일을 직접 열기
open index.html

# 방법 2: 로컬 서버
python3 -m http.server 8000
```

## Commands / 명령어

입력창에 `/`를 입력하면 명령어 힌트가 표시됩니다. `Ctrl+숫자`로도 트리거할 수 있습니다.

Type `/` in the input field to see command hints. Triggers also work with `Ctrl+number`.

| 명령어 | 설명 | Description |
|--------|------|-------------|
| `/1` | 레드 알럿 | Red alert |
| `/2` | 폭발 | Explosion |
| `/3` | 타겟 포착 | Target lock |
| `/4` | 긴급 통신 수신 | Incoming comms |
| `/5` | 데이터 버스트 | Data burst |
| `/6` | 보안 침해 | Security breach |
| `/7` | 위성 스캔 | Satellite uplink |
| `/8` | 추출 확인 | Extraction |
| `/9` | 카운트다운 | Countdown |
| `/0` | 시스템 스캔 | System scan |
| `/auto-type` | 자동 타이핑 on/off | Toggle auto-type |
| `/auto-event` | 자동 이벤트 on/off | Toggle auto events |
| `/auto-comms` | 자동 통신 on/off | Toggle dummy comms |
| `/sound` | 사운드 on/off | Toggle sound |
| `/name <이름>` | 콜사인 변경 | Change callsign |
| `/link` | P2P 연결 열기/닫기 | Open/close P2P link |
| `/link <코드>` | 다른 화면에 연결 | Connect to another screen |
| `/link-slot <N>` | 최대 연결 수 설정 | Set max connections |

## GitHub

**https://github.com/kochul2000/spy-screen-fui**

## License

MIT
