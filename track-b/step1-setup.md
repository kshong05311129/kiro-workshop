# Step 1: 프로젝트 설정

> 새 프로젝트 폴더를 만들고 샘플 데이터를 준비합니다.

## 진행 순서

### 1. 프로젝트 폴더 생성

바탕화면에 새 폴더를 만듭니다:
- 폴더 이름: `hotel-data-dashboard`

### 2. Kiro에서 폴더 열기

**File → Open Folder** → `hotel-data-dashboard` 선택

### 3. 샘플 CSV 파일 복사

다운로드한 `hotel_operations_april2026.csv` 파일을 프로젝트 폴더에 복사합니다.

또는 Kiro 사이드바에서 폴더로 파일을 드래그앤드롭합니다.

### 4. 데이터 구조 확인

CSV 파일을 클릭하여 내용을 확인합니다:

| 컬럼 | 설명 | 예시 |
|------|------|------|
| date | 날짜 | 2026-04-01 |
| reservation_id | 예약번호 | RES-240401-001 |
| guest_name | 투숙객명 | 김민수 |
| room_type | 객실 타입 | Standard/Deluxe/Suite/Premium Suite |
| room_rate | 1박 요금 | 300000 |
| total_amount | 총 결제액 | 645000 |
| nationality | 국적 | KR/US/JP/CN 등 |
| booking_channel | 예약 경로 | Direct/OTA/Agent |
| purpose | 목적 | Business/Leisure/Family/Honeymoon |

> 💡 30일간 90건의 현실적인 호텔 운영 데이터입니다.

## 확인

✅ Kiro 사이드바에 `hotel-data-dashboard` 폴더와 CSV 파일이 보이면 준비 완료!
