# Pickle Office · 피클 비서실

폰 홈 화면에 앱처럼 올려 두고 쓰는 개인 대시보드입니다.
`index.html` 한 파일(이미지 내장)로 동작하며 GitHub Pages로 서빙됩니다.

- **주소: https://didirididi1234-hash.github.io/Pickle-office/**
- 폰 브라우저(크롬·삼성 인터넷)에서 주소를 연 뒤 메뉴의 **홈 화면에 추가**를 누르면
  아이콘(P.)과 함께 앱처럼 뜹니다. (manifest: standalone 전체화면)

## 배포 메모

- GitHub Pages 소스는 **`gh-pages` 브랜치 / (root)** 입니다. `main`과 같은 내용을 올려 두었습니다.
- 내용을 고칠 때는 `index.html`을 수정하고 **`main`과 `gh-pages` 두 브랜치에 모두** 푸시하면
  1분 안에 사이트가 갱신됩니다.
  ```
  git add -A && git commit -m "..." && git push origin main
  git push origin main:gh-pages
  ```
- 파일: `index.html`, `manifest.webmanifest`, 아이콘 5종(192·512·maskable·apple-touch 180·favicon 32).
