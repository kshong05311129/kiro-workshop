# 사전 준비 체크리스트

> 실습을 시작하기 전에 아래 항목을 모두 완료했는지 확인하세요.

## 필수 준비 사항

### 1. 인터넷 연결된 노트북

Wi-Fi 연결이 안정적인지 확인해주세요.

### 2. Kiro IDE 설치

[kiro.dev](https://kiro.dev)에서 Mac 또는 Windows용 설치 파일을 다운로드합니다.

- **Mac**: `.dmg` 파일 다운로드 → 더블클릭 → Applications 폴더로 드래그
- **Windows**: `.exe` 파일 다운로드 → 더블클릭 → 설치 마법사 따라가기

### 3. 로그인 계정 준비

아래 중 하나로 로그인할 수 있습니다:

| 방법 | 설명 |
|------|------|
| **AWS IAM Identity Center** | 워크샵에서 제공하는 조직 계정으로 로그인 ✅ **이번 워크샵** |
| **Google 계정** | Gmail 있으면 바로 사용 가능 |
| **GitHub 계정** | [github.com](https://github.com)에서 가입 |
| **AWS Builder ID** | [profile.aws.amazon.com](https://profile.aws.amazon.com)에서 가입 |

> 💡 이번 워크샵에서는 **AWS IAM Identity Center** 방식을 사용합니다. Start URL과 리전 정보는 워크샵 당일 진행자가 안내합니다.

### 4. Node.js 설치 (MCP 서버 사용 시 필요)

MCP 서버 연결을 위해 Node.js가 필요합니다.

**Windows 설치:**

1. [nodejs.org](https://nodejs.org) 접속
2. **LTS 버전** (왼쪽 초록 버튼) 다운로드
3. 설치 마법사 실행 — **모든 옵션 기본값으로 진행**
4. ⚠️ "Automatically install the necessary tools" 체크박스가 나오면 **체크**

설치 확인 (Kiro 터미널 또는 명령 프롬프트에서):

```bash
node --version
npm --version
npx --version
```

세 명령어 모두 버전 번호가 나오면 성공!

**Windows에서 안 될 때:**

| 증상 | 해결 방법 |
|------|-----------|
| `node`를 찾을 수 없음 | PC 재시작 후 다시 시도 (PATH 반영) |
| PowerShell에서 `npx` 실행 차단 | 관리자 PowerShell에서: `Set-ExecutionPolicy RemoteSigned` 입력 후 Y |
| 권한 에러 | 명령 프롬프트를 "관리자 권한으로 실행" |

> 💡 **팁**: 설치 후 반드시 **PC를 재시작**하세요. PATH 환경변수가 바로 적용되지 않는 경우가 많습니다.

**Mac 설치:**

```bash
# Homebrew로 설치
brew install node

# 또는 nodejs.org에서 .pkg 다운로드
```

### 5. (선택) Git 설치 확인

Mac에서는 보통 사전 설치되어 있습니다.

**Windows**: [git-scm.com](https://git-scm.com)에서 다운로드 → 기본값으로 설치

터미널에서 확인:

```bash
git --version
```

> ⚠️ **로그인 문제가 있나요?** 워크샵 당일 진행자에게 문의해주세요. 대부분 Google 계정으로 바로 로그인 가능합니다.

## 체크리스트

- [ ] 노트북 준비 완료
- [ ] Kiro IDE 다운로드 완료
- [ ] 로그인 계정 준비 완료 (Google/GitHub/AWS Builder ID)
- [ ] 인터넷 연결 확인

> 💡 **팁**: 워크샵 전날까지 설치와 로그인을 완료해두시면, 당일 실습에 바로 집중할 수 있습니다.
