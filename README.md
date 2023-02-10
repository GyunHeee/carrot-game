# carrot-game
## 목적 
당근을 줍는 게임입니다. Javascript의 DOM객체 이해와 Web api이해를 위한 실습 프로젝트입니다. 
## 주요 기능
1. 시작버튼을 누르면 게임이 시작됩니다.
2. 지정된 시간안에 모든 당근을 클릭 시 "YOU WIN"이라는 팝업이 나옵니다.
3. 지정시간안에 모든 당근을 클릭하지 못하거나 벌레를 클릭하면 "YOU LOSE"라는 팝업이 나옵니다. 
4. 윗부분에 남은 시간이 나옵니다.
5. 남은 시간 밑에 현재 남은 당근의 개수가 나옵니다. 
6. stop버튼을 누르면 "Replay"라는 팝업과 함께 게임을 다시 할 지 선택하게 됩니다.

![ezgif com-video-to-gif (4)](https://user-images.githubusercontent.com/92011224/218050803-8a5f9c35-1e07-4958-a09b-ea2c4b7aea60.gif)
## 배운점
* html, css 마크업
* JavaScript DOM 객체
* element.classList
* css- visibility: hidden 속성과 display: none의 차이
* clearInterval(timer)
* audio 객체
## 어려운점
* 다양한 기능이 서로 관련된 경우가 많아서 힘들었습니다 -> 비슷한 기능을 함수로 묶어 재사용성을 높였습니다. 
## 더 배울점
* 기능별로 모듈화하기 (field, game, sound 등을 클래스 만들기)
* builder pattern을 이용하여 구조적으로 코드를 수정
