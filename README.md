# 📌 웃픈갤러리


## 프로젝트 소개

- 오픈갤러리 사이트 클론 프로젝트
- 약 2주 간의 짧은 프로젝트 기간으로 인해 필수 기능과 빠른 시일 내에 구현 가능한 기능에 초점을 맞췄습니다. 
- 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 프론트엔드와 백엔드가 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

### 개발 인원 및 기간

- 개발기간 : 2021/07/19 ~ 2021/07/30
- 개발 인원 총 5명
   -  프론트엔드 : 이종민, 이재현
   -  백엔드 : 최현정, 최명준, 김예랑

### 데모 영상

<a href="https://youtu.be/OOkNGPRC4F0">웃픈갤러리 시연영상 클릭</a>

<br>

## 적용 기술 및 구현 기능

### 적용 기술

> - Front-End : React, Styled-Component
> - Back-End : Python, Django, MySQL, Bcrypt, pyJWT, Docker, s3
> - Common : AWS(EC2,RDS), RESTful API

### 협업 도구
Slack / Git + GitHub / Trello, Notion를 이용해 일정관리, 현황을 관리하였습니다. 


### 프로젝트 후기
https://velog.io/@sui3422/Upoon-Gallery-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8


### Front-End 구현 기능

**<이종민>**
- 로그인 (카카오 소셜 로그인)
- 상세페이지 (페이지 내부 색 변경, 리뷰 업로드, 슬라이드 기능) 

### 상세페이지 기능
1.상품 내부 이미지 갯수에 따라 슬라이드 사이즈 변화
![slide](https://user-images.githubusercontent.com/80690729/129879625-28399435-5bda-42b1-b6c7-8b8c3b6efe4e.gif)

2. 버튼색상과 일치하는 색상으로 배경색 변경
![colorchange](https://user-images.githubusercontent.com/80690729/129879701-0f66fb6c-7843-49e9-90c3-4a22309a358b.gif)

3.리뷰 업로드 기능 (이미지 업로드 및 FormData 형식으로 통신)
![review](https://user-images.githubusercontent.com/80690729/129879810-4da621c8-849a-461b-9884-e42fac11dda2.gif)

4.벽돌형 레이아웃 (같은 작가의 연관작품)
![layout](https://user-images.githubusercontent.com/80690729/129879894-ba622330-e039-48a6-aa55-a51495fe5ef5.gif)


**<이재현>**
- 메인페이지 (슬라이드 기능)
- 리스트페이지 (Masonry 레이아웃 ,필터링, 페이지네이션 등)
 
### Backend 구현 기능

**<최현정>**
- 제품필터링 엔드포인트 구현
- 제품상세페이지 엔드포인트 구현

**<최명준>**
- 제품리뷰 엔드포인트 구현
- S3 Storage 활용 (리뷰 이미지 업로드 등)

**<김예랑>**
- 소셜 로그인기능 구현(카카오 API 활용)
- 장바구니 기능 구현 

<br>


## Reference

- 이 프로젝트는 [오픈갤러리](https://www.opengallery.co.kr/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
