# Learning_HTML_CSS_JAVASCRIPT

## [index](https://changhoji.github.io/html-css-javascript)

## [참고한 사이트](https://opentutorials.org/course/3084/)

## 22.08.16

### 의문
태그의 id는 고유한 것으로, 중복되게 쓰지 말아야 한다고 배움 -> 클래스 이용. 

그렇다면 파일이 달라도 중복된 id는 사용하지 말아야 하는가?

### 결론
구글링 해보니 [여기서](https://stackoverflow.com/questions/18268249/can-you-use-the-same-id-once-for-multiple-html-page) Same ID on differnet pages가 가능하다고 하고, 그게 일반적인 경우라고 한다. 

이를 이용해 서로 다른 html파일에서 id가 index인 ordered list를 공통적으로 디자인하는 css파일을 만들수 있겠다.

## 22.08.17

### 의문
[이 페이지](https://changhoji.github.io/html-css-javascript/CSS/%EC%83%9D%ED%99%9C%EC%BD%94%EB%94%A9/post/html_css.html)를 만드는 과정에서 결과는 html파일을 iframe으로 가져오면 되는데 코드는 어떻게 보여줘야 할지 고민이 됨.

### 결론1
[이 사이트](https://mothereff.in/html-entities)를 이용해 코드를 바꾸고 복사 붙여넣기하는 방식으로 해보았다. 다만 이렇게 하면 깃허브에 올려진 해당 코드의 파일과 실시간으로 동기화되는게 아니어서 만족하지 못하고 'html github code embed'로 검색해 더 찾아봤다.

### 결론2
[이 사이트](https://emgithub.com/)를 이용해 내 깃허브 저장소에 있는 코드를 임베드 할 수 있었다. 현재가 이상태

## 22.08.22

### 배운점
position 값 중 fixed를 이용하면 스크롤을 내려도 위치가 고정되기 때문에 항상 페이지 위쪽에 고정되어있는 유튜브 검색바나 메뉴바를 표현하기에 사용할 수 있을것 같다.