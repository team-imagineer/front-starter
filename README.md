# Front-starter

- 프로젝트를 위한 Vue.js + Nuxt.js 기본 템플릿입니다.

## Nuxt.js 에 대한 개요

- 어렵게 설명하지 않고 간단하게 설명하자면 뷰나 리액트와 같은 Single Page Application은 단점을 가지고 있습니다.
- 이러한 단점을 극복하기 위해 React는 Next.js, Vue.js는 Nuxt.js를 이용합니다.
- 그리고 이런 프레임워크를 사용하면 폴더 구조가 어느 정도 강제되어 협업에 유리한 점도 있습니다.
- 라우팅, 레이아웃, 페이지에 대한 개념을 익히면 사용하는데는 문제가 없을 것 같습니다.

## Vuetify 에 대한 개요

- material design에서 따온 UI Framework 입니다.
  - 가장 유명한 친구이지만 Vue3가 나왔음에도 아직 업데이트가 안되어 많은 사람들이 떠나가고 있는 추세인 것 같습니다.
  - 하지만 아직도 가장 인기가 많은 친구로 보이고, 추후 업데이트되면 다시 사람들을 끌어 모을 것이라 생각합니다.
- 어떻게 사용하나요?
  - 사용하고 싶은 컴포넌트를 [공식 문서](https://vuetifyjs.com/en/) > "UI Components 탭"에서 검색하거나 찾아보세요.
  - 코드 예시를 참고하여 컴포넌트를 추가해보세요.
  - 세세한 스타일을 바꾸고 싶다면, 해당 컴포넌트가 어떤 props를 필요로 하는지 참고하셔서 고치면 됩니다.
    - Style Props라고 CSS를 따로 작성하지 않고 스타일을 props를 통해 js로만 작성합니다. 몇 번 사용해보시면 금방 이해할 것입니다.
    - 마진이나 패딩같은 속성을 m, p 와 같은 props로 전달할 수 있습니다.

## Eslint와 Prettier, 그리고 pre-commit 이란?

- eslint: 코딩 컨벤션을 지키기 위한 룰들을 적어두고 지키게 하는 것
  - 에러가 있거나 혹은 코딩 컨벤션을 어긴 코드를 알려줌 (표시해줌)
- prettier: 코딩 컨벤션 때문에 쓰는 코드 포맷터
  - 사람마다 선호하는 탭 개수나 라인당 글 개수 등이 다를 수 있는데 이를 정해진 규측으로 포매팅해줌.
- pre-commit: commit 하기 전단계라고 생각하면 되는데, 이 개념이 왜 나오냐면 eslint나 prettier로 수정되지 않은 코드를 커밋해버리면 나중에 포맷을 맞추기 위해 쓸데없는 커밋을 해야하는 경우가 분명히 나오게 됨.
  - 이를 방지하기 위해 이 프로젝트에서는 commit을 하면 직전에 eslint와 prettier를 실행시켜줍니다. 만약 문제가 있다면 커밋

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).
