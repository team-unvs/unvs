# Website

이 기본 문서화 시스템 저장소는 [Docusaurus](https://docusaurus.io/) 도큐사우르스 플랫폼을 이용해서 만들어 졌습니다.

아주 간단하게 자신의 문서 정리 시스템, 위키, 블로그 시스템을 깃헙을 이용해서 만들 수 있습니다.

## 설치

yarn, npm 이런거 말고 온라인에서 바로 되도록, 이 저장소를 fork 하는 것으로 해결되도록 합니다.
설치가 머예요? 버튼 한 번 누르면 끝!!

## 로컬 구현

필요없습니다. 아닌가? 

그래도 제대로 나오는지 확인하기 위해 설정을 간단하게 로컬 피씨에서 실행하는 정도의 명령어를 정리해 둘 필요가 있어 보이네요.

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## 배포

깃헙액션을 통해 해당 브랜치로 빌드된 정적 페이지들이 자동 배포되도록 수정한다.

게다가 깃헙페이지를 통해 자동으로 해당 주소로 서비스가 운영되도록 한다.

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
