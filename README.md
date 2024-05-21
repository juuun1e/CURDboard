# < CURDboard >
- SpringDataJPA 
- datasource : h2 

<br>
<br>

## ⎷ Entity : 회원과 게시글의 연관관계(1:N)
1. 게시글 
    - 테이블명 : Post
        - id(bigint) : 게시글 번호 -> PK
        - title(String) : 게시글 제목
        - content(String) : 게시글 내용
        - write_time(Timestemp) : 작성 날짜
        - modify_time(TimeStemp) : 수정 날짜
        - username(String) : 작성자
     
2. 회원
    - 테이블명 : User
        - id(bigint) : 회원 번호 -> PK
        - name(String) : 회원 이름
        - email(String) : 회원 이메일
        - register_time(Timestemp) : 가입 날짜

<br>

## ⎷ 구현 API
1. 게시글 조회하는 API : 페이징 조회 / 단건 조회
2. 게시글 수정하는 API
3. 게시글 삭제하는 API



