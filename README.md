#  Watcha Classic
- Front: 김민석, 김은경, 이현범
- Back: 이태권, 박민하

![왓챠로고](https://user-images.githubusercontent.com/98795239/177035333-f286463f-b492-4117-877a-9935f32a14ae.png)


[시현 영상 보러가기](https://scrawny-opera-4c6.notion.site/ded2dbffac2140609d15bc3877219332)

<br>

## 프로젝트 소개
위코드 에서 진행한 팀 프로젝트
Frontend 3명, Backend 2명 으로 총5명이 한 팀으로 하나의 사이트를 클론 해보는 프로젝트
<br>SNS와 평점 데이터를 활용한 왓챠피디아를 모티브로 하여 클래식 영화 백과사전 사이트 구현
- 기간 : 2022.06.20 ~ 2022.06.30 (총 11일)
- 역할 : 상단 Navigation-bar 및 로그인 / 회원가입, 유저의 프로필페이지 담당

<br>

## 사용기술 스택
- Front-end: <img src="https://img.shields.io/badge/html5-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=Sass&logoColor=white"/> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=white"/> <img src="https://img.shields.io/badge/react-61DAFB?style=flat-square&logo=react&logoColor=white"/> <img src="https://img.shields.io/badge/ReactRouter-CA4245?style=flat-square&logo=ReactRouter&logoColor=white"/>
- Back-end: <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>

<br>

## Front-end 필수구현 기능
> ### 1. 회원가입 / 로그인 페이지
  - 유효성 검사, back-end API 통신
  - 상단 Navigation-bar,  로그인 / 회원가입 

> ### 2. 메인 페이지
  - 라이브러리 없이 이미지 슬라이드 구현
  - 3개의 API 한 페이지에 받아오기
  - Advanced Router 사용하여 각각의 목록 클릭시 path parameter id 값 불러오기

> ### 3. 상세 페이지
  - 스켈레톤, 평가 별점, 보고싶어요 댓글 UI 구현
  - <보고싶어요> 버튼 클릭 시 보고싶어요 페이지로 데이터 전송

> ### 4. 프로필 페이지
  - 회원정보 보여주기
  - <보고싶어요> 담긴 갯수 보여주기 
 
> ### 5. 보고싶어요 페이지
  - 메인 페이지의 컴포넌트 재사용
  - 사용자가 보고싶어요 기능 사용한 데이터 받아오기

<br>

## 담당 기능 MVP

![로그인 효과 더 큰 화면 (1)](https://user-images.githubusercontent.com/98795239/177004527-ca256165-1530-497c-8247-f29d0e8879af.gif)
![회원가입 효과 더 큰 화면  (1)](https://user-images.githubusercontent.com/98795239/177004786-4c1f9619-75b3-4087-be4f-e8b6727447ef.gif)

- 정규표현식을 사용하여 객체 안에 로직을 선언 한 후 `map`메소드 안에서도 로그인, 회원가입 창 각각의 `input`에 로직을 전달 후 유효성 검사를 바탕으로 각각 효과를 구현 할 수 있었습니다.
- 로그인, 회원가입 창에서 입력한 값을 2개의 `useState`로 저장 후 각각의 `input` 창에서 **삭제버튼** 클릭시 `value` 값을 지울 수 있도록 구현 했습니다. 







<br>

## 소통에 사용한 협업 툴
### Slack
<img width="942" alt="스크린샷 2022-07-01 오후 3 48 13" src="https://user-images.githubusercontent.com/50426259/176840075-30907e6a-8be6-4914-88d3-fe0d3742ad9c.png">

- Back-end와 자료 공유 및 개인적인 소통

### Trello
![trello](https://user-images.githubusercontent.com/50426259/176840626-5bc5b445-4c0b-4259-93bd-56d9f63f2485.gif)
- 백엔드와 프론트엔드 모두 참여하는 티켓 생성 
- 앞으로 해야 할 작업들과 스프린트로 진행해야 할 작업, 완료된 작업을 각각 목록에 따라 분류 하고 네이밍과 Label을 붙임으로써 팀과 지속적으로 의사소통

### Notion
![image](https://user-images.githubusercontent.com/50426259/176840968-aab75ef3-4a5c-4497-a532-db539a297b58.png)
- 매일 진행되는 Stand-up meeting에서 각자의 진행 상황과 팀원들끼리 피드백과 필요한 사항들을 주고 받으면서 다시 의기투합 하는 시간을 가짐

### ERD
![image](https://user-images.githubusercontent.com/50426259/176841194-db70fa46-6f62-4a65-8638-3c2562092a32.png)
- Back-end의 ERD 자료 구성을 참고하여 Mockdata 및 실제 서버와 통신시 불러오는 key값 확인

<br>

## 문제해결 아카이브
> ### 팀으로써 고민한 부분과 해결
  - 서로 어떤 작업을 진행 중이고 그 과정에서 협의가 필요한 부분이 있는지 파악 할 수 있는 의사소통 방법에 대한 고민
    - 아침 10시 팀원 30분씩 스탠드업 미팅을 진행하며 서로의 진행 상황을 공유하고 팀원과 피드백을 주고 받는 시간을 가짐
    - 미팅시에 팀장의 모니터로 한자리에서 노션을 활용하여 프론트와 백엔드가 서로 이해 할 수 있게 각자의 진행 상황을 설명 하면서 팀내 회의록을 작성하여 기록해둠
    - Trello를 활용하여 각자 맡은 임무의 작업목록을 직관적으로 분류해둠
    
  - 협업을 하다보니 프론트엔드와 백엔드 간의 데이터를 분석하는 과정에서 중간에 수정하는 부분이 있어 의견에 충돌이 있었다.
    - 회의실에서 팀원들과 회고를 하면서 진행상황에 관하여 지금 할 수 있는 부분과 어려울 것 같은 부분을 상의하며 메타인지를 할 수 있는 시간을 가짐
    - 데이터를 추가하는 과정이 백엔드 분들에겐 복잡한 과정일 수 있어 시간내에 구현 가능한 기능들을 협의하여 정하고 그에 따라 각자가 맡은 임무를 착실히 수행
    
  - 영화 정보를 기반으로 한 사이트이다 보니 사진 저작권에 대한 고민
    - 저작권이 없는 년도가 오래 된 영화들을 보여 줄 수 있는 사이트를 만들기로 협의함
    - 올드한 영화들을 모아 사이트 자체의 컨셉도 클래식한 영화들의 정보를 볼 수 있는 왓챠클래식으로 결정
    
  - 프론트엔드 3명이서 어떻게 프로젝트를 관리해야 효율적으로 작업을 할 수 있는지 고민
    - Github을 활용한 프로젝트 관리 / Trello를 사용하여 Task로 관리 
    - Github Pull Request를 사용하여 멘토님들께 코드리뷰를 받고 각자 자신의 코드에 대해 리펙토링 하는 시간을 가짐
    

    
    





