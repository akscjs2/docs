# 웹사이트

이 웹사이트는 현대적인 정적 웹사이트 생성기인 [Docusaurus 2](https://docusaurus.io/)를 사용하여 만들어졌습니다.

### 설치

```
$ yarn
```

### 지역 개발

```
$ yarn start
```

이 명령은 로컬 개발 서버를 시작하고 브라우저 창을 엽니다. 대부분의 변경 사항은 서버를 다시 시작할 필요 없이 실시간으로 반영됩니다.

### 빌드

```
$ yarn build
```

이 명령은 `빌드` 디렉토리에 정적 콘텐츠를 생성하고 모든 정적 콘텐츠 호스팅 서비스를 사용하여 제공할 수 있습니다.

### 배치

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

호스팅을 위해 GitHub 페이지를 사용하는 경우, 이 명령은 웹사이트를 구축하고 `gh-pages` 브랜치로 푸시하는 편리한 방법입니다.
