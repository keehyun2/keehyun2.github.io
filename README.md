# keehyun2.github.io

**이 저장소는 `dev-wiki` 소스 저장소에서 빌드되어 배포된 결과물입니다.**

- 라이브 사이트: https://keehyun2.github.io
- 소스 저장소: `keehyun2/dev-wiki` (Quartz 4 기반 위키)
- 배포 커밋은 `deploy: keehyun2/dev-wiki@<sha>` 형식이며, `<sha>`는 빌드 당시
  소스 저장소의 커밋을 가리킵니다.

## 주의

- 여기 있는 파일은 모두 빌드 산출물이므로 **직접 수정하지 마세요.**
  내용·구조 변경은 소스 저장소(dev-wiki)에서 수행한 뒤 다시 배포해야 합니다.
- 직접 수정한 내용은 다음 배포 때 덮어써지거나 사라질 수 있습니다.
- `.nojekyll` 파일은 GitHub Pages의 Jekyll 처리를 끄는 역할을 하므로 삭제하면 안 됩니다.

## 구조 (빌드 결과물)

| 경로 | 내용 |
|------|------|
| `concepts/` | 개념 문서 페이지 |
| `summaries/` | 요약 문서 페이지 (하위 폴더: `database/`, `development/`, `ide/`) |
| `sources/` | 원본 문서 페이지 |
| `tags/` | 태그 인덱스 페이지 |
| `static/` | 아이콘, OG 이미지, 검색 인덱스(`contentIndex.json`), giscus 테마 |
| `index.html`, `index.css`, `prescript.js`, `postscript.js` | Quartz 런타임 및 스타일 |
| `sitemap.xml`, `index.xml` | 사이트맵 / RSS |
