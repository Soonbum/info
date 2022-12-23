<p align="center">
  <a href="https://ifcjs.github.io/info/">ifc.js</a>
  |
  <a href="https://discord.gg/FXfyR4XrKT">디스코드</a>
</p>

<img src="banner.png">
<h1>IFC.js docs <img src="https://ifcjs.github.io/info/img/logo.svg" width="32"></h1>

![opencollective](https://opencollective.com/ifcjs/tiers/badge.svg)

이 리포지토리는 [IFC.js](https://github.com/IFCjs)의 공식 문서입니다. [여기](https://ifcjs.github.io/info/)로 방문하실 수 있습니다. 여기에는 다음과 같은 프로젝트 관련 모든 정보를 포함하고 있습니다:

- IFC.js 이면의 동기.

- 라이브러리의 모든 모듈에 대한 소개.

- API 레퍼런스.

- 단계별 튜토리얼.

- 제작자들의 비공식 글.

- 협업 시스템 및 패트리온(patreon).

- 커뮤니티 하이라이트.

- 소셜 네트워크 링크.

## 상태

이 문서는 [docusaurus](https://docusaurus.io/)를 이용해 만들어졌습니다. 이것은 자동으로 생성된 것이 아니라 손수 만든 것입니다. 동시에 IFC.js는 빠르게 진행되는 프로젝트이므로, 프로젝트가 통합될 때까지 문서를 집중적으로 유지보수 해야 합니다.

저희는 이것이 추가적인 노력이 든다는 것을 인지하고 있지만 일반적이고 기계적인 API를 피하고 좀 더 인간적이고 시작하기 쉬운 것을 만들고 싶습니다.

이 유지보수에는 주로 API 메소드 및 클래스를 업데이트하고, 커뮤니티에서 요청한 대로 새로운 튜토리얼을 만드는 작업이 포함됩니다. 이것은 진행중인 작업이므로 누락되거나 잘못된 것이 보이면 주저하지 말고 저희에게 알려주십시오.

## 빠른 설정

첫째, 이 프로젝트를 다운로드하거나 리포지토리를 복제한 다음에 `yarn install`로 모든 디펜던시(dependencies)를 설치하십시오. 그 다음에는 `yarn start`로 프로젝트를 로컬에서 시작할 수 있습니다.

다른 언어로 프로젝트를 시작하려면, `--locale` 플래그를 사용하면 됩니다:

- 일본어: `yarn start --locale ja`

- 중국어: `yarn start --locale zh`

## 내용

이 프로젝트는 다음 폴더들로 구성되어 있습니다:

- **docs**: 마크다운 문서.

- **blog**: 블로그의 마크다운 문서.

- **i18n**: 다른 언어로 된 docs의 마크다운 문서.

- **src**: 멋지게 만들기 위해 docs에서 사용된 react 구성요소들.

- **static**: 이미지와 아이콘.

## 기여(공헌)하기

도와주고 싶습니까? 훌륭해요!

이 문서들은 매우 간단한 마크다운을 사용하여 React에 익숙하지 않더라도 매우 쉽게 편집하고 새로운 문서를 만들 수 있습니다. 마크다운 문서를 복사하기만 하면 올바른 스타일로 문서에 표시될 것입니다.

- 부담없이 [커뮤니티](https://discord.gg/FXfyR4XrKT)에 새로운 튜토리얼을 제안하고 pull request로 여기에 제출하십시오.

- 만약 여기에 없는 어떤 튜토리얼을 놓친다면, issue 또는 [디스코드 서버](https://discord.gg/FXfyR4XrKT)에 요청하실 수 있습니다.

가져오기를 해서 미리 만들어진 구성요소를 사용하실 수 있습니다. (방법을 찾기 위해 기존 `.jsx` 파일들을 확인하십시오) 그게 아니더라도 이 문서들을 더 근사하게 만들기 위해 새로운 구성요소들을 만들 수도 있습니다.
