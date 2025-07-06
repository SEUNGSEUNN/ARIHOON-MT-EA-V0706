# ARIHOON MP EA - V0706

최종 통합 자동매매 시스템 (MT4용 Expert Advisor)

## ✅ 소개
이 EA는 MACD 기반 진입, 마틴게일 구조, 반익절, 트레일링 스탑, HUD 출력 등을 포함한 완전 자동화 전략입니다.

전략 문서 기준 버전: `ARIHOON-MP-EA-0706`

## 🧠 주요 기능
- MACD 골든/데드 크로스 기반 진입
- 손실 시 마틴게일 1~2차 진입
- 반익절(50% 청산) 및 트레일링 스탑 자동 적용
- SL/TP 라인 시각화, 추세 HUD 출력
- 계좌 제한 및 사용 기간 제한 포함
- 전략 테스터에서 완전 자동 테스트 가능

## 📂 파일 구성
- `arihoon-ea-full-integrated.mq4` : 소스코드
- `arihoon-ea-full-integrated.ex4` : 실행파일 (컴파일 필요)
- `strategy-spec.md` : 전략서 문서

## 📌 사용 방법
1. MetaTrader4 → MQL4 → Experts 폴더에 `.mq4` 파일 복사
2. MetaEditor에서 열고 컴파일 (`F7`)
3. 차트에 적용 후 파라미터 설정

## 🔒 제한 사항
- 허용 계좌번호: `774011`
- 사용 가능 기간: `2025.12.31`까지
