# 고품질 음악 스트리밍 사이트

2023.04-2023.06


## 프로젝트 개요

고품질의 음악 스트리밍을 위해서만 많은 금액을 지불해야 하기 때문에 학생들을 위한 무료 고품질 음악 스트리밍 사이트를 제작하였습니다.

## 개발 환경

+ Node.js
+ 데이터베이스 : MySQL


## 주요 기능

### [메인 화면]

  <img src="https://github.com/wqp99w/read-me_image/blob/main/ooad/%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85.jpg" width="600" height="600"/>

+ ID 중복 확인이 가능하며, 사용자의 음식 선호도를 입력합니다.
  

### [음악 요청 게시판]

  <img src="https://github.com/wqp99w/read-me_image/blob/main/ooad/%EB%A1%9C%EA%B7%B8%EC%9D%B8.jpg" width="600" height="600"/>

  + 로그인에 성공하면 Splash 화면으로 전환되며, 음식 추천 화면으로 이동됩니다.
  
### [음악 요청 게시글 세부정보]

  ![위치좌표](https://github.com/wqp99w/read-me_image/blob/main/ooad/%EC%9C%84%EC%B9%98%EC%A2%8C%ED%91%9C.jpg)

  + 현재 위치가 어딘지를 표시하며, 이를 통해 현재 좌표를 구할 수 있습니다.
  
### [음악 검색 기능]

  ![날씨](https://github.com/wqp99w/read-me_image/blob/main/ooad/%EB%82%A0%E3%85%86.jpg)

  + 현재 좌표를 이용하여 기상청 API를 사용하여 현재 위치의 날씨 정보를 받아올 수 있습니다.
  +   하늘 상태와 온도 정보만 필요하기 때문에 해당 정보들만 가져오는 모습입니다.
  
### [음악 재생 기능]

  <img src="https://github.com/wqp99w/read-me_image/blob/main/ooad/%EC%9D%8C%EC%8B%9D%EC%B6%94%EC%B2%9C%ED%99%94%EB%A9%B4.jpg" width="300" height="600"/>

  + 음식 추천받기 버튼을 누르면 음식을 추천합니다.

  <img src="https://github.com/wqp99w/read-me_image/blob/main/ooad/%EC%B6%94%EC%B2%9C%EB%A1%9C%EA%B7%B81.jpg" width="400" height="150"/>

  + 날씨에 따른 음식 종류와 사용자의 선호도에 따른 음식 종류를 각각 선택하여 음식을 추천합니다.
  
