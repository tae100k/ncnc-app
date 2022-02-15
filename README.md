# 더블엔씨 니콘내콘 모바일 웹페이지 클론 과제

원티드 프리온보딩 부트캠프 - 더블엔씨 모바일 웹페이지 클론 과제 리포입니다.

## 배포

- [배포링크](https://ncnc-app.vercel.app/)

## 요구 사항

다음 페이지들을 클론하는 것이 이번 과제의 주된 요구사항이었습니다.

- [니콘내콘 홈페이지](https://ncnc.app/)
- [카테고리별 브랜드 페이지](https://ncnc.app/categories/67)
- [각 브랜드당 제품 페이지](https://ncnc.app/brands/63)
- [제품별 상세설명 페이지](https://ncnc.app/items/137)
- 사이드 메뉴

## 기술 스택

- NextJS
- TypeScript
- SCSS + CSS Modules
- ESLint + Prettier
- Cypress

## 로컬 환경 구동

프로젝트 클론

```bash
  git clone https://github.com/wanted-pre-onboading-10/ncnc-app.git
```

프로젝트 디렉토리 들어가기

```bash
  cd ncnc-app
```

패키지 설치 및 프로젝트 시작

```bash
  npm install && npm run dev
```

## 팀 소개

## 팀원

| 이욱창                                                                                                     | 김태희                                                                                                     | 문현돈                                                                                                     | 이경은                                                                                                     |
| :--------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| ![](https://user-images.githubusercontent.com/78027252/153702187-d9d6a705-9b36-4bc7-a178-7a0657893b4d.png) | ![](https://user-images.githubusercontent.com/78027252/153702225-f9c8fb23-b7af-454d-9c97-4b7119a06214.png) | ![](https://user-images.githubusercontent.com/78027252/153702229-2c97a545-a682-4867-b78e-5028c7774201.png) | ![](https://user-images.githubusercontent.com/78027252/153702159-776cb78e-59ca-4c0a-bab5-742f5998d4e0.png) |
| [@wook95](https://github.com/wook95)                                                                       | [@tae100k](https://github.com/tae100k)                                                                     | [@hyundonny](https://github.com/hyundonny)                                                                 | [@2kyung19](https://github.com/2kyung19)                                                                   |

## 팀원별 역할 및 회고

### 김태희

- 역할
  - 리덕스 툴킷을 사용하여, 메시지 추가, 메시지 삭제, 메시지 정렬 등의 기능을 구현하는 역할을 맡았다.
  - (구현) messageSlice에 add, delete액션을 만들었고, 커스텀 훅 useMessage를 통해 useSelector를, useMessageAction useDispatch를 할 수 있도록 구현하였다.
- 회고
  - 이번 프로젝트하면서 작성한 블로그 : [[김태희 - Messanger Service]](https://www.notion.so/7245b5bb8cf341a08513b483f2676de4)
  - 메시지를 추가하면, 채팅 내용 + 유저 정보 형태로 메시지 데이터 모델을 추가해야 했다. 그래서 유저 정보 리덕스를 구현한 팀원에게 질문하고 설명을 들으면서 해결하였고, 이 때 협업의 중요함을 느꼈다. 이를 바탕으로 본인이 작성한 리덕스를 채팅창 코드에서 사용할 때는 팀원분이 해당 리덕스를 잘 이해하고 사용할 수 있도록 줌을 통해 의사소통하는 시간을 가졌다.

### 문현돈

- 역할:
  - 레이아웃, 헤더, 사이드 메뉴, 고객센터 페이지, e2e 테스트 작성 담당. 개인 블로그를 NextJS로 만든 경험 덕에 빠른 속도로 전반적인 레이아웃과 고객센터 페이지를 만들 수 있었다. 뿐만 아니라 이전 과제에서 사이드 메뉴를 만든 경험이 있어 이번에도 효율적으로 사이드 메뉴를 구현할 수 있었다. 다만 참고용으로 주어진 Figma 디자인과 실제 홈페이지 간에 차이가 존재해 어떤 방식으로 디자인을 구현해야 할 지 쉽게 파악하지 못한 부분도 더러 있었다. 이런 경우에는 팀원들과 함께 사용자가 가장 사용하기 편한 방식에 대해 논의했고, 이를 기반으로 페이지를 구현했다.

- 회고
  - 이번 과제에서 처음으로 e2e 테스트 코드를 작성해봤다. Cypress 라이브러리에 대해 처음 알게 되었고 복잡하지는 않지만 내가 만든 부분의 기본적인 기능을 전부 테스트하는 코드를 작성해볼 수 있었다. Cypress 공식 문서가 워낙 깔끔하게 작성되어 있었기에 공식 문서를 기반으로 내가 원하는 부분을 테스트해볼 수 있어 만족했다. 앞으로는 e2e 테스트와 unit 테스트 코드를 적극적으로 활용해보고 싶다.

### 이경은

- 역할
  - 홈 화면 및 상품리스트 구현
  - 무한 캐러셀 구현
  - 아이템 박스 컴포넌트 구현

- 회고
  - NextJS를 처음 경험해보면서, 한 단계 성장했다!
  - 이번에는 type이나 api 규칙도 정하는 등 과제를 진행하면 할 수록 팀내 규칙이 쌓여가는 것 같아 뿌듯했다!

### 이욱창

- 역할
  - 상품 상세 페이지 구현
  - 3단으로 움직이는 버튼클릭,옵션 선택, 구매 기능

- 회고
  - 백엔드와 소통할 할수 없는 상황에서, 데이터를 잘 만져 원하는 대로 바꾸면서 자바스크립트에 대해 더 잘 알수 있었습니다!
  - SSR을 통해 pre-rendering을 시켜주는 경험이 좋아 앞으로도 쭉 next를 공부할 예정입니다!
