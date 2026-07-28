# 하루성경

[하루성경](https://apps.apple.com/) 앱의 개인정보처리방침과 이용약관을 공개하는 정적 사이트입니다.

- [개인정보처리방침](https://johau91.github.io/harubible/privacy/)
- [이용약관](https://johau91.github.io/harubible/terms/)

## 고치는 법

이 저장소의 HTML을 직접 수정하지 마세요. 원본은 앱 저장소의
`dfc2013-mobile/apps/bible/src/data/legalDocuments.ts` 하나이며, 앱 화면과 이
사이트가 같은 파일을 씁니다. 복사본을 두면 두 곳이 조용히 어긋납니다.

```bash
# 앱 저장소에서
pnpm generate:legal-site        # HTML 재생성
# 생성된 apps/bible/legal-site/ 내용을 이 저장소로 옮겨 커밋
```

문의: reu0691@kakao.com
