# OTT 서비스 넷플릭스 클론코딩
<br>
<br>

### 설명
React, Typescript와 ES6문법, 다양한 리액트 라이브러리를 공부하기 위해 TMDB API를 이용한 Netflix UI를 클론한 페이지입니다.

### 사용된 기술
1. Axios, React-query를 사용해 TMDB Data를 처리하였습니다.
2. Framer-motion 를 사용해 팝업, 슬라이드 애니메이션을 구현했습니다.
3. react-hook-form을 사용하여 검색을 구현했습니다.
4. Styled-Components를 사용하여 UI 퍼블리싱 했습니다.

### 이슈
Array map 메소드를 사용하는 중 map 콜백함수 인수로 생성되는 currentValue가 수정이 안되는 이슈가 발생하여 새로운 배열을 반환받고 난 후 변경하였습니다.
<br>
자식요소의 이벤트 발생이 부모요소 이벤트도 불러오는 이슈가 발생하여 stopPropagation을 사용해 이벤트 전파를 중단시켰습니다.


### 실행
npm init

npm run start
