# nolog for Hugo
- 원본 repo: https://github.com/Sharknia/nolog
- 대충 Hugo에 맞게 수정해서 사용..
## 수정한 거
- Hugo에서 `content/post/{slug}/index.md`로 파일 작성 필요 → 기존 템플릿에서 slug 속성 추가하고 pages.ts에서 처리
- date 속성 생성일시로 변경 후 `/src/models/pages.ts`에서 생성일시 속성의 이름이 date일 때 date로 처리하게 수정
- 이미지도 `content/post/{slug}` 경로로 저장되게 수정