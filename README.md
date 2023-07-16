## 소개팅 웹사이트 (AMANNA)

### About "AMANNA" 프로젝트
1. 저희가 제공하고자 하는 서비스는 직장인을 위한 소개팅입니다.
2. 코로나 바이러스 방역 완화로 인한 오프라인 행사및 커뮤니티가 활성화된 사회적 분위기 활성화 목적
3. 직장인들의 소개팅 연결 및 커뮤니티 활성화 목적

#### 진행 기간 
-> 2023년 5월 25일 ~ 2023년 6월 21일

#### 개발 환경 
* Language: Java, JavaScript, Html/CSS, jQuery
*  Framework: Spring
* Database: Oracle
* IME: Eclipse

##### Reference site
>직장인 소개팅


### 담당업무
* 관리자 (공지사항 작성, QNA, FAQ 작성, 리뷰관리)
* 유저 (리뷰작성)
* Main page (공지사항, QNA, FAQ)

### 왜 게시판 기능을 선택하였나?
프로그래밍에서 가장 기초적이면서 중요한 기능은 **CRUD**(Create Read Update Delete)라고 생각합니다.

데이터를 작성, 읽기, 수정, 삭제 기능을 가진 대표적인 파트가 게시판이라고 생각해서 담당하게 되었습니다. 

*******************
관리자(공지사항 작성, QNA, FAQ 작성, 리뷰관리)
#### 관리자 모드
* 리뷰관리 (회원들이 작성한 리뷰 확인 및 삭제)
* FAQ (회원들이 문의한 내용에 답변)
* 공지사항, FAQ관리(회원 또는 신규 회원들을 위한 글 작성)
<img width="50%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/8f7aab98-8020-4f3c-8915-ef85d764162a">


#### 리뷰 관리
* **페이징 처리**로 한페이지에 10개의 글이 보이게 되어있습니다
* 관리자모드에서는 리뷰 및 댓글에 삭제만 할 수 있게 되어있습니다
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/2528ff94-8826-40aa-b718-d3042d920277">
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/0d20920e-c127-4f2e-b85f-19dc5bb94e4b">

#### 공지사항 및 FAQ 관리
* **페이징 처리**로 한페이지에 10개의 글이 보이게 되어있습니다
* 관리자 페이지에서는 회원들이 볼 수 있는 페이지랑 다르게 글을 작성, 수정, 삭제를 할 수 있는 기능이 있습니다
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/2ad33775-94ec-49a1-9ffa-8332b9c3a35a">
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/29d28ef3-8564-4179-bec6-d4b5e9957791">

#### QNA 관리
* 관리자 페이지에서는 고객이 작성한 비밀글에 비밀번호 없이 확인을 할 수 있습니다
* 댓글이 완료가 되면 자바스크립트를 이용하여 글자의 색의 변화를 주어, 댓글 여부를 확인 할 수 있게 하였습니다
* 관리자는 댓글을 수정 및 삭제를 할 수 있습니다
* 작성자가 글을 수정하게 되면 답변 상태는 “수정 후 답변 대기”로 전환이 됩니다
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/4a1f73ce-a403-4a1e-9b6c-e37eaa5c4801">
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/2f942990-affa-4819-9e46-e79fe3471c08">

***
메인 페이지
#### 만남후기 (Main)
* 리뷰페이지에서는 작성된 글, 사진 등을 확인 할 수 있습니다
* **로그인**이 되어 있는 **상태이면** 댓글을 작성 할 수 있습니다
* 댓글은 댓글 **작성자**만이 수정 및 삭제를 가능합니다.
* 비회원 이거나 리뷰 작성자면 조회수는 **증가 되지 않습니다**
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/e58c8f3b-2a92-4c62-98d0-cd92924c290e">
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/f9197b54-0d7b-496f-bb1e-5cc9bafd6a18">

#### FAQ, 공지사항 (Main)
* 관리자가 작성한 글을 열람할 수 있습니다
* 자바스크립트를 이용하여 버튼을 클릭시 해당 작성글의 내용을 볼 수가 있습니다
* 해당 카테고리만 버튼을 누르면 해당 카테고리의 글만 볼 수 있습니다(FAQ)
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/dd315df3-6dcf-4c50-9371-efe336027e91">

#### QNA 관련 (Main)
* QNA는 회원가입이 안되어 있어도 누구나 작성이 가능하다
* 작성한 글을 제목 또는 아이디로 검색을 해서 찾을 수 있다
* 비밀글일 경우 글작성을 할때 입력한 비밀번호와 일치할 경우에만 작성글을 열람할 수가 있다
* 작성자만 글을 삭제 및 수정이 가능하다
* 관리자의 댓글을 확인 할 수 있다
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/a9c49b74-9e47-4b39-9a83-fa4289155c09">
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/05b074c1-e28c-4bda-82e5-551e97f819d0">
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/b135f56c-608d-43e3-88bb-1096feb1ce70">

****
유저(리뷰 관련)
#### 리뷰 작성페이지
* 자바스크립트를 이용하여 제목, 내용의 글자수를 제한하고, 입력된 값이 없을때에는 **alert** 기능을 이용하였습니다
* 리뷰 관련 Controller에 **MultipartFile** 방법을 이용하여 첨부 파일을 저장할 수 있게 하였고, 파일이 저장이 될때에는 중복을 방지하기 위하여, 파일명에 **난수**를 더하여 경로와 DB에 저장이 됩니다
* 첨부파일 기능은 선택적이고, **ajax**를 이용하여 미리보기 기능을 가지고 있습니다
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/bd6a8277-7fe2-46cc-8183-2037b6e93aca">


#### 작성 리뷰 확인 확인 및 수정/삭제
* My page에서 회원이 작성한 리뷰를 확인하고, 수정/삭제를 할 수 있게 하였습니다
* 해당하는 **글번호**를 기준으로 DB상에서 수정 및 삭제가 됩니다
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/41f6502f-afc4-4c97-ac34-cfa3c2e19b91">
<img width="30%" src="https://github.com/parkbs6974/Final_Project/assets/120395647/b71fae22-f942-4d4c-829a-f8d2564829ce">

******
### 소감
* 가장 구현 하고 싶었던, CRUD (Create Read Update Delete) 기능을 Spring Framework을 이용하여 완성 할 수 있어서 좋았습니다
* CRUD 기능을 기반으로 Ajax, 파일 첨부, 페이징 처리 같은 부가적인 기능을 구현 할 수 있었서 2차 프로젝트 보다 더 발전된 기능을 구현 할 수 있었습니다.

## 악쉬운점
* 프로젝트 기간동안 기술적으로 힘들어 하는 팀원들에게 도와주는 과정에서 설명이 부족하여 아쉬웠습니다.

-> 공부를 할떄 기초적인 부분을 좀 더 구체적으로 공부하고, 다음에는 팀원들이 좀 더 구체적으로 이해 할 수있게 준비를 하겠습니다.
* 구현하고 하였던 API를 이용한 e-mail기능을 구현하지 못한 점이 아쉬웠습니다.


-> 비록 프로젝트가 끝이 났지만 , 구현하고 싶었던 내용을 추가할 예정입니다.
