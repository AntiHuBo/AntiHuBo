# AntiHuBo (AI Control Tower)

> 여러 AI 도구를 동시에 쓸 때, 인간이 병목이 되지 않도록

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## 🤔 문제

AI 도구가 발전하면서, 역설적으로 **인간이 병목**이 되고 있습니다.

```
Claude Code에서 코드 생성 시켜놓고...
ChatGPT에서 문서 작성하다가...
Cursor에서 리팩토링 기다리는 중...

"어디서 응답 왔지?"
"내가 뭘 하고 있었지?"
"지금 뭐부터 봐야 하지?"
```

여러 AI 도구를 동시에 사용할 때:
- 🔄 컨텍스트 스위칭 비용 증가
- 🧠 인지 부하 (cognitive load) 증가  
- ⏰ "응답 왔나?" 확인하느라 시간 낭비

## 💡 해결책

**AntiHuBo**는 여러 AI 도구의 상태를 한눈에 보여주는 데스크톱 앱입니다.

### 핵심 기능

- **📊 통합 대시보드**: 모든 AI 도구 상태를 한 화면에서
- **🔔 스마트 알림**: 응답 완료, 에러 발생 시 알림
- **📝 컨텍스트 리마인더**: 도구로 돌아갈 때 "뭐 하고 있었는지" 표시
- **🔗 관련 작업 연결**: 비슷한 주제의 다른 도구 작업 연결

### 지원 AI 도구

| 도구 | 상태 | 모니터링 방식 |
|------|------|--------------|
| Claude Code | ✅ 지원 | 프로세스 + 로그 |
| ChatGPT | ✅ 지원 | Browser Extension |
| Cursor | ✅ 지원 | 수동 + Vision |
| Perplexity | 🚧 예정 | 기여 환영! |

## 🚀 설치

### 요구사항

- Node.js 18+
- Chrome (ChatGPT 모니터링용)
- Claude API 키 (Vision 폴백용)

### 설치 방법

```bash
git clone https://github.com/[your-username]/antihubo.git
cd antihubo
npm install
npm run dev
```

## 🏗️ 아키텍처

자세한 내용: [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md)

## 🛣️ 로드맵

자세한 내용: [docs/ROADMAP.md](docs/ROADMAP.md)

## 🤝 기여하기

기여를 환영합니다! [CONTRIBUTING.md](CONTRIBUTING.md)를 참고해주세요.

## 📄 라이선스

[Apache License 2.0](LICENSE)

---

**AntiHuBo** - AI 시대, 인간이 병목이 되지 않도록 🚀
