# Board
Spring Boot를 이용하여 개발한 게시판 입니다.

## 개요
Spring boot를 이용하여 기본적인 웹 게시판을 만드는 프로젝트입니다.

## 개발 환경
### 백엔드
```
* Java 11
* Docker
* MySql
* JPA
* Spring Security
* OAuth 2.0
* IDE : Intellj
```

### 프론트엔드
```
* HTML
* Bootstrap
* IDE : Intellj
```

## 요구사항 분석

회원가입
- 아이디는 4~12자 특수문자를 제외한 영어, 숫자만으로 구성되어 있다.
- 닉네임은 2~10자 특수문자를 제외한 영어, 숫자만으로 구성되어 있다.
- 비밀번호는 6~16자 영어, 숫자, 특수문자로 구성되어 있으면 각각 하나씩 사용해야한다.
- 아이디, 닉네임, 비밀번호는 공백 및 빈칸이 있으면 안된다.

로그인
- 로그인을 하지 않을 경우 일부 게시글을 이용할 수 없다.
- 구글을 통해 로그인을 할 수 있다.
- 회원가입을 통해 로그인을 할 수 있다.

게시글
- 게시글은 작성, 삭제, 수정, 검색이 가능해야한다.
- 게시글은 본인및 관리자만 삭제할 수 있다.
- 게시글의 제목과 내용은 빈칸이 올 수 없다.

## DB 설계
![image](https://user-images.githubusercontent.com/68494227/179522933-293b3e3c-b26d-44ef-9b9e-d4cccead5bfb.png)



## API 설계
![image](https://user-images.githubusercontent.com/68494227/180915538-548ac73c-779f-43fb-9ab4-154989cd74c0.png)

