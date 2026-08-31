# marketing

앱 3종의 무예산(월 0원) 성장 전략 문서.

- **웹**: https://jinmo78.github.io/marketing/
- **본문**: `index.html` — 단일 HTML 파일, 빌드 도구·의존성 없음
- **로컬 확인**: `open index.html`

공개 저장소이지만 `index.html`에 `noindex` 메타태그가 있어 검색엔진은 색인하지 않습니다.
실제로 색인을 막는 건 이 메타태그입니다. `robots.txt`는 프로젝트 페이지 구조상
크롤러가 읽지 않으므로(사이트 루트가 아님) 효력이 없습니다.

## 대상 앱

| 앱 | 판정 | Google Play | App Store |
|---|---|---|---|
| 나의 스크랩 | 주력 | [com.jinmo.myscrap](https://play.google.com/store/apps/details?id=com.jinmo.myscrap) | [id6793531420](https://apps.apple.com/kr/app/id6793531420) |
| 루미 (App Store명: 루미 이야기) | 조건부 | [com.jinmo78.lumi](https://play.google.com/store/apps/details?id=com.jinmo78.lumi) | [id6794529020](https://apps.apple.com/kr/app/id6794529020) |
| insquare | 반쪽 출시 | 비공개 테스트 (공개 주소 없음) | [id6771190865](https://apps.apple.com/kr/app/id6771190865) |

소개 사이트: https://my-app-policies-blond.vercel.app/ko

## 다음 행동

1. 루미 소개 페이지에 스토어 링크 추가 (현재 누락 = 전환 누수)
2. 루미 단위 경제성 계산 — 보상형 광고 1회 수익 vs 열어주는 대화의 토큰 원가
3. insquare Play 테스터 16~18명 모집 (개인 계정이므로 12명 14일 요건 해당)
4. 세 앱 D1 / D7 / D30 리텐션 표 작성

## 수정 방법

```
git add -A && git commit -m "내용 수정" && git push
```

푸시 후 1~2분이면 GitHub Pages에 반영됩니다.
