# Luuvish Article

Hugo로 구성한 `luuvish.github.io/luuvish-article`용 정적 사이트입니다.

## 로컬 실행

```bash
hugo server -D
```

브라우저에서 `http://localhost:1313/luuvish-article/` 또는 `http://localhost:1313/`를 확인하세요.

## 새 글 작성

```bash
hugo new content posts/my-new-post.md
```

생성된 파일에서 `draft = false`로 바꾸면 배포 시 공개됩니다.

## 배포

`main` 브랜치에 push하면 GitHub Actions가 자동으로 빌드 후 GitHub Pages에 배포합니다.
