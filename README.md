# CoinTrader — 자동 암호화폐 매매 프로그램

> 업비트(Upbit) 기반 자동 트레이딩 도구 (Windows 64-bit)

## 다운로드

| 파일 | 설명 |
|------|------|
| [최신 버전 다운로드](https://github.com/seatoskymee/Trading_Coin_02_Python-Release/releases/latest/download/CoinTrader_latest.exe) | 항상 최신 버전 (URL 고정) |

또는 [전체 릴리즈 목록](https://github.com/seatoskymee/Trading_Coin_02_Python-Release/releases)에서 버전별 파일을 받을 수 있습니다.

## 주요 기능

- **5가지 전략** — RSI 스캘핑, MACD 모멘텀, 변동성 돌파, 볼린저 스퀴즈, EMA 크로스오버
- **AUTO 모드** — ADX·ATR·BB 분석으로 시장 상황에 맞는 전략 자동 선택
- **실시간 포트폴리오** — 전체 수익률 / 투입 대비 손익 한눈에 확인
- **웹 모니터** — Flask + ngrok으로 모바일 브라우저에서 원격 모니터링
- **자동 업데이트 알림** — 앱 시작 시 새 버전 감지 → 다이얼로그 알림

## 실행 환경

- Windows 10/11 64-bit
- 별도 Python 설치 불필요 (독립 실행 EXE)

## 설정

최초 실행 후 생성되는 `config.yaml`에서 API 키·전략·위험 관리 파라미터 설정

## 버전 이력

| 버전 | 주요 변경 |
|------|----------|
| v0.1.25 | 도움말 메뉴 버전 체크, 릴리즈 노트 다이얼로그, 업데이트 배지 |
| v0.1.24 | 웹 모니터 포트폴리오 현황 카드 추가 |
| v0.1.23 | 포트폴리오 현황 카드 (전체 수익률 / 투입 대비 손익) |
| v0.1.22 | 웹 모니터 URL 하이퍼링크, 감시 종목 다크 테마 수정 |
| v0.1.20 | 웹 모니터링 (Flask + ngrok) 모바일 대시보드 |