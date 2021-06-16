# 다이어트 렌즈 SRS 문서

- 관리자 : DoGooRi (정현호)

- 참여자 : dhtngus4921 (오수현), kkt9601 (김경태)

- 문서 버전 : 0.2

<br>

## 문서 확인 페이지

현재 이 문서는 브라우저를 통해 편리하게 보실 수 있습니다.

[문서 페이지 이동](https://dogoori.github.io/srs-dietlens) 통해 확인해주세요.

> 혹시 페이지에서 문서가 갱신 되지 않는 경우 브라우저 캐시를 삭제해주세요.

<br>

## 참여자를 위한 로컬 서버 설치 및 구동 가이드

1. 현재 작업 컴퓨터에 Node.js가 없다면 Node.js를 먼저 설치해주세요 (12.x LTS 추천) [12.x LTS 다운 링크](https://nodejs.org/dist/latest-v12.x/)
2. 아래 명령어를 통해 npm 패키지 설치

```bash
npm i docsify-cli -g
```

3. 아래 명령어를 통해 프로젝트 git clone

```bash
git clone https://github.com/DoGooRi/srs-dietlens
```

4. clone 한 프로젝트 경로로 이동 후 아래 명령어를 통해 서버 구동

```bash
docsify serve
```

5. 아래 내용이 정상적으로 출력되면 브라우저에서 http://localhost:3000 을 통해 서버 구동 확인

```bash
Serving [경로]/srs-dietlens now.
Listening at http://localhost:3000
```

<br>

## 참여자 권장 작업 도구

1. Git Client - [SourceTree](https://www.sourcetreeapp.com/)
2. Markdown Editor - [Typora](https://typora.io/)

3. Code Editor - [Visual Studio Code](https://code.visualstudio.com/)