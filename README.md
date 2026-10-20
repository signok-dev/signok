# @signok/sdk 이슈 · 문의

SignOK(싸인오케이) 전자서명 v2 API TypeScript SDK [`@signok/sdk`](https://www.npmjs.com/package/@signok/sdk)의 버그 제보, 기능 요청, 사용 문의를 받는 저장소입니다.

이 저장소에는 소스 코드가 없습니다. 사용법과 API 문서는 npm 패키지에 들어 있습니다.

## 설치와 문서

```bash
npm install @signok/sdk
```

| 문서 | 내용 |
|---|---|
| [README (npm)](https://www.npmjs.com/package/@signok/sdk) | 설치, 빠른 시작, 메서드 요약, 에러 코드 |
| `node_modules/@signok/sdk/FIRST_CYCLE.md` | 처음 연동할 때 완주할 한 사이클 (서명요청 → 상태 확인 → 문서·이력보고서 다운로드) |
| `node_modules/@signok/sdk/AGENTS.md` | AI 코딩 에이전트용 작업 지침 |
| `node_modules/@signok/sdk/llms.txt` | 전체 메서드 레퍼런스 |

## SDK를 쓰려면

1. SignOK에 가입합니다. 테스트는 스테이징 https://stg-doc.signok.com , 운영은 https://doc.signok.com 입니다.
2. SignOK팀(docu@kica.co.kr / 02-360-3040)에 연락해 API ID(client_id)와 Secret Key(client_secret)를 발급받습니다.
3. SignOK 화면에서 템플릿을 1개 이상 등록합니다.

## 이슈 등록

[Issues → New issue](https://github.com/signok-dev/signok/issues/new/choose)에서 유형을 골라 양식에 맞춰 작성해 주세요.

- **버그 제보:** SDK가 예상과 다르게 동작할 때
- **기능 요청:** 필요한 메서드나 개선 사항이 있을 때
- **사용 문의:** 사용법이 궁금할 때

등록 전에 [기존 이슈](https://github.com/signok-dev/signok/issues?q=is%3Aissue)에 같은 내용이 있는지 확인해 주세요.

버그 제보 양식에서는 SDK 버전, Node.js 버전, 환경(staging/production), 호출한 메서드, 에러 정보(`code`, `serverMessage`, `endpoint`), 재현 코드를 받습니다.

> [!WARNING]
> **이슈는 누구나 볼 수 있습니다.** client_secret, access_token, 서명자 이름·연락처 같은 개인정보, 계약서 내용은 올리지 마세요.
> 에러를 공유할 때는 `code`, `serverMessage`, `endpoint`만으로 충분합니다.

## 다른 문의

| 문의 | 연락처 |
|---|---|
| 영업 문의 | SignOK팀 · docu@kica.co.kr · 02-360-3040 |
| 기술 문의 | 개발팀 · kangms9098@kica.co.kr · 02-360-3156 |

## 보안

**보안 취약점은 공개 이슈로 등록하지 마세요.** kangms9098@kica.co.kr 로 메일 제목에 `[보안]`을 붙여 비공개로 알려 주세요. SDK 버전, 영향 범위, 재현 방법을 함께 보내 주시면 확인 후 수정과 공개 일정을 협의합니다.

client_secret이 코드 저장소나 로그에 노출되었다면 즉시 SignOK팀(docu@kica.co.kr / 02-360-3040)에 연락해 재발급받으세요.

## 라이선스

`@signok/sdk`는 MIT 라이선스로 배포됩니다. Copyright (c) 2026 Korea Information Certificate Authority, Inc. (한국정보인증)

SignOK API와 서비스 이용은 SignOK 서비스 이용약관과 별도 계약을 따릅니다.
