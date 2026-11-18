# Denote Top Ads

[EN](README.md) · [ZH](README.zh.md) · [JA](README.ja.md) · KO · [ES](README.es.md) · [NL](README.nl.md) · [DE](README.de.md) · [FR](README.fr.md)

다음 캠페인에 참고할 광고를 찾아보세요. Denote는 광고 1,000만 건 이상을 추적하고 매주 순위를 갱신합니다. 무료 계정으로 지난 한 주 동안의 게임 또는 앱 광고를 세 가지 순위표에서 각각 최대 10개까지 확인할 수 있습니다. [Denote 광고 순위 살펴보기](https://denote.net/top-ads).

| 무료 순위표 | 무엇을 볼 수 있나요? |
| --- | --- |
| 인기 광고 | 지난주에 가장 많은 관심을 받은 광고를 확인하세요. |
| 급상승 광고 | 전주보다 인기도가 가장 크게 오른 광고를 찾아보세요. |
| 신규 광고 | 새로 발견된 광고를 초기 인기도 순으로 살펴보세요. |

## 첫 주간 순위표 받기

OpenClaw 작업 공간에서 다음 명령을 실행하세요. Python 3가 필요합니다.

```sh
git clone https://github.com/Denote-Business/denote-top-ads.git skills/denote-top-ads
```

1. 새 세션을 열고 “Denote로 어떤 광고를 찾을 수 있어?”라고 물어보세요.
2. [Denote 무료 계정 만들기](https://denote.net/user/register). 이미 계정이 있다면 로그인하세요. `top_ads:read` 권한을 가진 Denote API 키를 만들거나 기존 키에 이 권한을 추가하세요.
3. 에이전트의 보안 설정에 키를 `DENOTE_API_KEY` 이름으로 저장한 뒤 “지난주 앱 광고 순위를 보여 줘”라고 요청하세요. 세 가지 순위표가 바로 표시됩니다. 분야를 지정하지 않으면 게임 광고를 보여 줍니다.

**순위 · 광고 제목 · 광고주 · 형식 · 게재 플랫폼 · 미리보기**

## 광고 자세히 보기

“급상승 광고 2위를 자세히 보여 줘”라고 요청해 보세요. Top Ads Pro 또는 Business 계정에서는 제공 가능한 광고 성과와 잠재고객 정보도 확인할 수 있습니다. 세 가지 주간 순위표는 무료입니다.
