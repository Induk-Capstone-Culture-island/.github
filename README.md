# 너만의 전시회

## 요구사항 분석
### 회원
#### 일반 등급
- 회원을 가입, 탈퇴, 로그인, 로그아웃이 가능해야한다.
- 회원 정보는 이름, 아이디(이메일 형식), 비밀번호, 생년월일, 전화번호, 찜목록, QnA리스트를 포함해야한다.
- 회원 PASSWORD는 영문자와 숫자 포함 8자 이상이여야 한다.
- 회원은 본인의 개인정보를 조회 및 수정이 가능해야한다.
- 정보 수정은 아이디만 제외하고 가능해야 한다.
- 회원은 일반 회원과 관리자 등급으로 나누어진다.
- 회원은 본인이 작성한 QnA리스트/찜한 목록을 확인할 수 있다.
#### 관리자 등급
- 관리자는 회원 목록을 조회할 수 있다
- 관리자는 이름 또는 아이디(이메일)로 검색하여 회원 정보를 열람할 수 있다.
- 관리자는 일반 회원의 상태를 블락/해제 시킬 수 있다.
### 전시회
- 전시회 등록과 삭제, 수정은 관리자만 가능하다.
- 전시회 리스트 선택시 정보를 확인할 수 있어야한다.
- 전시회 정보에는 제목, 시작일, 마감일, 장소, 지역, 썸네일, 소개글, 운영 시간이 포함되어야 한다.
- 전시회 분류별 검색을 할 수 있어야한다.
- 전시회 정보는 전시중/종료예정전시(7일)/종료된 전시 3가지로 분류한다
- 전시회 검색은 제목, 장소(강남, 성북)로 검색할 수 있어야 한다
- 로그인한 사용자는 전시회를 찜할 수 있다.
- 전시회 리스트에는 페이지 처리를 하지 않는다.
### QnA 게시판
- 로그인한 사용자는 본인의 게시글을 작성, 수정, 삭제가 가능하다
- 관리자만 재게시물로 답변 및 삭제를 할 수 있는 권한이 있다
- 게시물에는 제목, 내용, 작성일 포함되어야 한다.
- 다른 사람의 질문은 제목만 확인할 수 있고 내용은 볼 수 없다
