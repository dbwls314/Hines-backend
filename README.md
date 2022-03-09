# Hines 
> [오늘의집](https://ohou.se/store?utm_source=brand_google&utm_medium=cpc&utm_campaign=commerce&utm_content=e&utm_term=%EC%98%A4%EB%8A%98%EC%9D%98%EC%A7%91&source=14&affect_type=UtmUrl&gclid=Cj0KCQiA2ZCOBhDiARIsAMRfv9KqcY4mcWWZikC6z5zRQa7ZkFj4jcVxD_ZFBb1CgGwjTPNQPmBfBhQaAi7yEALw_wcB)
> '오늘의 집' 사이트의 다양한 기능 중 커머스 기능을 중심으로, '몇 십년 뒤의 집'이라는 컨셉 하에 우주 속 다른 행성들의 땅을 소개하고 필요한 물품 판매를 목적으로 하는 사이트.

# 프로젝트 개요
## 📆 기간
- 2021.12.13 ~ 2021.12.24 (12일)

## 👥 멤버
- backend : `이유진`, 장도원, 제갈창민
- frontend : 이지현, 홍정빈, 황주영</br>
[Frontend github](https://github.com/wecode-bootcamp-korea/27-2nd-Hines-frontend)

<br>

## 🏊🏻‍♂️ 목표
- 다양한 툴(Trello, Notion, Slack, Github)을 사용함으로써 의사소통 능력 증대
- 초기 세팅부터 전부 실제 사용할 수 있는 서비스 수준으로 기획 및 배포까지 구현
- 화려하고, 고난이도의 로직을 구현하기보다는 그동안 학습했던 지식들을 2주 간의 팀 프로젝트에 복습 및 다진다는 것이 궁극적 목표

<br>

## 🛠 기술 스택 & 협업 툴
`Backend` : Python 3.8, Django 4.0, Mysql 8.0

`Common` : Slack,  Github, Trello, Notion

<br>

## 💻 구현기능 ( 기여도 35% )
- 소셜로그인
- 메인페이지
- 제품 상세페이지 [ 담당 기능 ]
- 제품 리뷰 포스팅 [ 담당 기능 ]
- 장바구니
- 주문 확인 페이지
- CSV 데이터 작성 및 데이터 입력


<br>

## [ 구현 담당 기능 ]
#### 1. Product Detail
- 제품 `상세 정보 반환`하는 상세페이지 API 구현

#### 2. Review
- 제품 `리뷰 등록` 및 `리뷰 정보 반환`하는 API 구현
- offset:limit을 활용한 `pagination` 구현 

<br>

----------

<br>

## 모델링
[ERD url](https://drive.google.com/file/d/13y8nRCN6WYFtsMzS5BUNi1MNyUJPcacA/view?usp=sharing)

<img width="800" alt="image" src="https://user-images.githubusercontent.com/90857450/157402621-f6b52714-e8d0-4479-b711-0853325130a6.png">


<br>

## 🎞 시연 영상

#### [ 하인즈 프로젝트 유튜브 링크 ](https://www.youtube.com/watch?v=Z4Hw1AQc_og)

<img width="1415" alt="image" src="https://user-images.githubusercontent.com/90857450/157430426-72a17ef2-1ed7-43f0-a0bd-ebf2416c6422.png">

#### [ 제품 상세 정보 ]

![gifit_1646814391470 (1)](https://user-images.githubusercontent.com/90857450/157402088-4512fdf4-1831-4182-8984-2e4b98ba635a.gif)


#### [ 제품 리뷰 ]

![gifit_1646814311519](https://user-images.githubusercontent.com/90857450/157401856-f16722a6-957f-48fe-a6a8-dcb7ce6d24b9.gif)

<br>

## Reference
- 이 프로젝트는 [오늘의집](https://www.google.com/search?gs_ssp=eJzj4tVP1zc0zCopKc8tMchRYDRgdGDw4nkzY8nrrhlv5s54s3wiAL8EDec&q=%EC%98%A4%EB%8A%98%EC%9D%98%EC%A7%91&rlz=1C5CHFA_enKR980KR980&oq=%EC%98%A4%EB%8A%98%EC%9D%9C&aqs=chrome.3.69i57j0i512l2j46i10i199i465i512j46i175i199i512j0i512l3j0i10i512j0i512.2653j0j15&sourceid=chrome&ie=UTF-8) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무 수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제가 될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
