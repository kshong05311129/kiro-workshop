# 트랙 B: 엑셀 데이터 분석 & 시각화 도구

> IT/데이터팀을 위한 실습 — Kiro로 데이터 분석 자동화 도구를 만들어봅니다.

## 🎯 목표

호텔 운영 데이터(CSV)를 업로드하면 자동으로 핵심 KPI를 계산하고, 차트로 시각화하며, 인사이트를 요약하는 웹 도구를 만듭니다.

## 만들 것

- 📊 CSV 파일 업로드 & 파싱
- 📈 핵심 KPI 자동 계산 (점유율, ADR, RevPAR 등)
- 📉 Chart.js 기반 시각화 (라인/바/도넛 차트)
- 📋 데이터 테이블 & 필터링
- 💡 요약 인사이트 자동 생성

## 기술 스택

- **단일 HTML 파일** (빌드 도구 불필요)
- **Tailwind CSS** (CDN)
- **Chart.js** (CDN)
- **Papa Parse** (CSV 파싱, CDN)
- 모든 로직은 브라우저에서 실행 — 서버/DB 불필요

## 소요 시간

⏱️ 90분

## 사전 준비

- Kiro IDE 설치 & 로그인 완료 (3부 참고)
- 샘플 CSV 파일 다운로드: [`hotel_operations_april2026.csv`](../samples/hotel_operations_april2026.csv)
