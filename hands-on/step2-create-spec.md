# Step 2: Spec 만들기

> Kiro에게 "호텔 고객 응대 도우미"를 만들고 싶다고 알려줍니다.

## 진행 순서

### 1. New Spec 클릭

Kiro 패널(왼쪽)의 **Specs** 섹션에서 **+** 버튼을 클릭합니다.

![](<../.gitbook/assets/image (3).png>)





### 2. 프롬프트 입력

아래 내용을 복사하여 붙여넣기 합니다:

```
롯데호텔 고객 응대 도우미를 단일 index.html 파일로 만들어주세요.

기능:
1. 외국어 고객 문의 입력란
2. 언어 자동 감지 표시
3. 한국어 번역 결과 표시
4. 문의 유형 자동 분류 (예약/시설/서비스/불만/기타)
5. 적절한 답변 자동 생성
6. 답변을 고객 언어로 역번역

기술 조건:
- Tailwind CSS는 CDN으로 로드
- 모든 JavaScript는 HTML 안에 인라인으로 작성
- npm이나 빌드 과정 없이 브라우저에서 바로 실행
- 데모용 샘플 번역 데이터 내장 (실제 API 연동 불필요)
- 롯데호텔 브랜드 느낌의 깔끔한 UI (골드/네이비/화이트)
- 반응형 디자인
```

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

오른쪽 Chat 인터페이스에서 "Build a Feature" 를 선택 후, "Submit answer" 버튼을 클릭합니다.

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

### 3. 각 단계 검토

Kiro가 순서대로 문서를 생성합니다:

**① Requirements (요구사항)**

Kiro가 "이런 기능들이 필요하군요"라고 정리합니다. 내용을 읽어보고 괜찮으면 **"Move to design phase"** 를 클릭합니다.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>



**② Design (설계)**

화면 구성과 데이터 흐름을 설계합니다. 확인 후 다음 단계로 진행합니다.&#x20;

"Continue" 버튼을 클릭합니다.

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>



아래와 같이 "Generate Design" 버튼을 클릭합니다.

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>





<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>





**③ Task List (작업 목록)**

실행할 작업 목록이 생성됩니다. 이것이 AI가 실제로 수행할 "할 일 목록"입니다.

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

## 확인

✅ `.kiro/specs/` 폴더 아래에 문서들이 생성되었으면 성공!

> 💡 **핵심**: 각 단계에서 마음에 들지 않는 부분이 있으면 채팅으로 "\~를 수정해줘"라고 요청할 수 있습니다. Spec은 언제든 수정 가능합니다.
