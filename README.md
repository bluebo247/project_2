# 캠핑인들의 커뮤니티 README
![intro](https://github.com/kimdaegeunn/project_2/assets/153577525/3ee97899-651f-4ce9-b293-14d28369c84a.png)  
  배포 URL :


## 프로젝트 소개
+ 수백만 캠핑인들의 경험, 노하우, 정보를 공유할 수 있는 커뮤니티입니다.
+ 캠핑장의 종류, 테마등으로 캠핑장을 서치할수있고 캠핑장의 상세정보를  얻을수 있다.
+ 캠핑장의 조회수를 통해 인기많은 캠핑장을 실시간 차트로 볼 수 있다.
+ 여러 캠핑인들의 캠핑요리, 캠핑팁, 캠핑리뷰, 캠핑모임등 게시판을 통해 만나볼 수 있다.

<br>

## 개발 기간

- Front : 2024.02.26 ~ 2024.02.29
- back-end : 2024.03.01 ~ 2024.03.05

## 팀원 구성 

| **팀장** | **팀원** | **팀원** | **팀원** |
| :------: |  :------: | :------: | :------: |
| **김대근** | **김은지** | **장준희** | **조수호** |


<br>

## 개발 환경

- Front : HTML, JavaScript, jquery
- Back-end : 공공데이터 활용, Nodejs, express, mysql
- 데이터 관리 : oracledb
- 협업 툴 : Discord, Github
- 배포환경 : AWS

## 페이지별 기능 

### [메인페이지]
- 메인페이지로 접속 초기화면입니다.
- 메인페이지에는 검색, 각 카테고리, 각 게시판 등 우리사이트의 주요기능을 접할 수 있다.
- 홈버튼을 누르면 메인페이지로 다이렉트 되도록 설정, 소개 페이지는 차트들로 캠핑 소개 페이지 <br> 작성(다양한 그래프를 통해 인기장소와 캠핑의 인기 척도를 파악할 수 있도록 제작)
- 메인페이지의 슬라이드 되는 캠핑장은 전국의 새로운 캠핑장을 소개합니다.또한 DB를 촤신순으로 정렬하여 최신 10개의 데이터를 나열되도록 설계하였다.
- 카테고리 바로 밑에 원하는 키워드를 바로 서치할 수 있도록 검색창을 구현, 키워드만 검색해도 원하는 정보를 바로 얻을 수 있도록 구현하였다.
- 메인 페이지 최하단은 각 팀원이 구현한 게시판으로 바로 이동할 수 있도록 구현, 또한 최신 게시글 6개가 차례대로 보이도록 설계하였다.
![main](https://github.com/kimdaegeunn/project_2/assets/153582101/d6ba33d8-3a72-41b8-b273-9639c8609bcf)

### [로그인, 회원가입]
- 로그인 버튼을 누르면 해당 모달창이 뜨도록 구현. form을 이용해 아이디와 비밀번호를 누르면 <br> 로그인 할 수 있도록 디자인 하였다. 로그인이 성공하면 게시판 열람과 글쓰기 기능이 활성화 된다,
- 회원가입페이지는 현재 기술이 미약하여 기본적인정보만 인서트 되도록 하였고 추후에 암호화, 유효성검사등 추가할 예정이다.
<img width="1920" alt="login" src="https://github.com/kimdaegeunn/project_2/assets/153582101/e5237538-f91b-4794-a716-887ac402107c">
![register](https://github.com/kimdaegeunn/project_2/assets/153582101/22926f0c-e74e-4299-ac5a-979c8de2a51d)




### [카테고리 페이지]
- 각 카테고리별 캠핑장을 보기 쉽게 분류되어 사용자들의 접근성을 높혔다.
![detail](https://github.com/kimdaegeunn/project_2/assets/153582101/f6c32e08-7065-4ac2-ae13-c590622fd346)


### [캠핑장 상세정보페이지]
- 캠핑장의 상세 정보를 볼 수 있는 화면이다.
- 캠핑장의 실데이터를 기반으로 작성되어 있다.
- 데이터베이스에 정보를 바탕으로 일반야영장, 자동차야영장, 카라반, 글램핑으로 나누어 각 페이지로 리다이렉트 될 수 있도록 페이지를 분할하였다.
- 추천과 찜하기 버튼이 있어 사용자들이 정보를 얻는데도 기여할 수 있다.
![realDetail](https://github.com/kimdaegeunn/project_2/assets/153582101/28eebaae-5a71-49e6-86c1-c06e4102cf9e)"

### [차트]
- 캠핑장의 조회수를 통해  인기캠핑장들이 실시간으로 차팅되는 페이지입니다.
- 캠핑인들의 캠핑장 선택요건, 캠핑인들의 변화추이를 차트로 보기쉽게 접할 수 있습니다.
![charts](https://github.com/kimdaegeunn/project_2/assets/153582101/ee93ba5b-a715-49c5-9d85-048bc87c7b54)"


### [실시간채팅]
- 웹소켓을 이용하여 간단한 실시간 채팅을 구현하였다.
![chat](https://github.com/kimdaegeunn/project_2/assets/153582101/b7f57302-91a4-4ccf-8e37-abe706b439cb)"



## 추가 개발(보완) 사항
- 챗봇고도화
- 실시간 채팅 고도화
- 지도 맵 마커 추가
- 회원가입 암호화
- 대부분의 기능들을 보완

## 프로젝트 후기

### 🧒김대근

서로 감정 상하지 않고 마무리하는 것이 주된 목표였고 , 각자의 스킬업을 첫째로 생각하며 프로젝트의 완성도가 떨어지더라도 부족한 부분을 채우기위해 팀원 모두 고생했습니다.
그러다보니 시간에 쫒기며 프로젝트를 하느라 트러블슈팅내용은 기록하지 못하였다. 미약한 지식이지만 팀장으로 팀원들이랑 공부할 수 있어서 감사했고 소중한 경험이였습니다.
다음 프로젝트는 체계적으로 설계해서 보다 효율적으로 진행할 수 있도록 노력하겠습니다.

<br>

### 👧김은지

해당 프로젝트로 NodeJS와 Express, MySQL을 이용해 DB서버를 구축하고 활용하는 방법을 공부 했는데요, 이를 구현하는데 한계를 느꼈고 팀장님과 팀원들의 도움을 받아 완성할 수 있었습니다. 이번 프로젝트를 통해 하나의 서버와 이것을 구현한 웹페이지를 만들어 큰 성취감을 느꼈고, 한편으로 나의 부족한 점, 더 보완 할 점을 찾을 수 있었습니다. 다음 프로젝트에서 더 발전할 수 있는 멋진 계기가 되었네요. 함께 해주신 팀원분들께 감사의 말씀 드리고싶습니다. 다음 프로젝트도 화이팅 합시다!!
<br>

### 👶장준희

이번 프로젝트에 참여하게된 장준희입니다. 이번 DB기술과 노드JS기술을 사용하는데에 어려움을 느껴 팀장의 도움으로 더 배우는 시간을 가지게되어 프로젝트를 늦게시작하였으나 결과물은 미완성이지만 모든 기능들은 구현하는데에는 성공하게되어 큰 기쁨과 성취감을 느꼈습니다. 프로젝트를 준비하는데 같이 고생한 조원들에게 감사하고, 다음 프로젝트는 더 열심히 준비하여 좋은 결과물을 만들겠습니다.
<br>

### 🧑조수호

이번 프로젝트는 공부하는 시간이 70% 정도였던 인상깊은 프로젝트였습니다. 팀원으로써 아는 것도 있지만 모르는 것도 많아서 같은 팀원들과 팀장에게 도움을 많이 받았습니다.  또한 협업하는 방법을 배웠고 커뮤니케이션의 중요함을 다시한번 알게되는 프로젝트였습니다. 프로젝트를 진행하다보니 javascript의 부족함이 많이 느껴졌습니다. 다음프로젝트는 열심히 준비하여 완성도를 높일 수 있도록 기여하겠습니다.
<br>
