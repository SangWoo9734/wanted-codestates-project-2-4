# 원티드 프리온보딩 프론트엔드 코스 - 디에이그라운드

✨[결과물 보러가기]()✨

## 사용 스택

<p>
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" />
  <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white" />
  <img src="https://img.shields.io/badge/react--icons-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/redux-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/react--redux-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/react--router--dom-CA4245?style=for-the-badge&logo=React-Router&logoColor=white" />
  <img src="https://img.shields.io/badge/flicking-orange?style=for-the-badge" />
</p>

## 요구 사항

  - [x] [상단 Tab bar]는 Click을 통해 각각의 Tab으로 이동할 수 있도록 구현합니다. Tab 간 이동 시 슬라이딩 애니메이션을 넣어주세요.
  - [x] [공유하기] 기능은 해당 컨텐츠 링크를 새 창으로 띄우는 것으로 대체합니다.
  - [x] [좋아요] 기능은 API가 따로 제공되지 않으므로 local storage 등을 통해 브라우저 refresh 전까지 count가 관리될 수 있도록 구현합니다. (최초 조회 시에는 API 내 like_cnt 만큼 좋아요 숫자가 보여져야 합니다)
  - [x] [새로 올라왔어요] 의 Carousel View 는 5초에 한번씩 바로 다음 컨텐츠로 슬라이딩 애니메이션 처리가 되면서 이동하도록 구현하며, 마지막 컨텐츠일 경우 가장 처음 컨텐츠가 보여지도록 구현합니다.
  - [x] [새로 올라왔어요] 의 컨텐츠는 API 내 like_top = 1 인 컨텐츠만 보여져야 합니다.
  - [x] [더보기] 버튼을 눌렀을 때 모든 컨텐츠가 각 sector에 맞게 조회되어야 합니다.
  - [x] [구독하기] 버튼을 눌렀을 때 [https://sandbank.io](https://sandbank.io) 로 새 창을 띄우는 것으로 대체합니다.
  - [x] 전역 데이터 관리(redux, mobx, anyting else..) 를 도입하여 구현해야 합니다.
  - [x] 버튼 등 컴포넌트에 대한 액션 수행 시 앱에 구현되어있는 reaction을 참고하여 구현해주시기 바랍니다. (Click 시 Animated한 백그라운드 색상 변경 등)
  - [x] 앱을 실제로 받아 분석을 진행해야만 정확한 UI를 구현할 수 있습니다. [둘러보기] 로그인이 가능하니 참고해주세요.
  - [x] 프론트엔드 서버는 `localhost:8888` 으로 설정해주시기 바랍니다.

## 기능구현
  - 1팀 : 탭, Redux Setting

  - 2팀 : 카드 컴포넌트

  - 3팀 : 상태페이지 구성


## 팀원 소개

| 이름         | 깃허브                                        | 역할 |
| ------------ | --------------------------------------------- | --- |
| 강동진       | [jinn2u](https://github.com/jinn2u)           | |
| 박상우       | [SangWoo9734](https://github.com/SangWoo9734) |카드 컴포넌트 제작 및 내부 기능 구현 |
| 신항민       | [ssinking91](https://github.com/ssinking91)   | |
| 이장민       | [leo-xee](https://github.com/leo-xee)         | |
| 오카무라카에 | [kaehehehe](https://github.com/kaehehehe)     | | 
| 허민         | [hhhminme](https://github.com/hhhminme)       | |
| 전호용       | [mooroom](https://github.com/mooroom)         | |
