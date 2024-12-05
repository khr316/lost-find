# 분실물&습득물 찾기 웹 서비스 플랫폼 제작<br>(Lost and Found Platform)


## [프로젝트 확인](https://khr316.tistory.com/entry/KEPCO-luckyPYNK-sprint)
<br><br>



# **luckyPYNK - 분실물/습득물 관리 웹 플랫폼**

## **프로젝트 개요**
luckyPYNK은 분실물 및 습득물을 관리할 수 있는 **웹 플랫폼**입니다.  
사용자는 **게시판 형식**으로 분실물 및 습득물을 **등록, 검색, 관리**할 수 있으며,  
**회원 간 쪽지 기능**을 통해 소통을 지원합니다.  

사용 친화적이고 직관적인 **UI/UX**를 제공하는 것을 목표로 합니다.


## **프로젝트 정보**
- **프로젝트 기간:** 2024.07.04 ~ 2024.07.15 (2주)  
- **팀 구성:** 4명  
  - **박소라, 유영훈, 노광우, 김혜림(본인)**


## **역할 분담**

### **박소라**
#### **백엔드**
- **회원가입 페이지**: 아이디 중복 체크, 필수 입력 처리, 비밀번호 확인 일치 여부 검증
- **로그인 페이지**: DB 연동 로그인 기능, 오류 메시지 처리
- **관리자 페이지**: 회원 탈퇴, 게시글 및 댓글 삭제 기능
- **게시글 페이지**: 글 작성자/관리자 삭제 기능

#### **프론트엔드**
- **메인 페이지, 로그인/회원가입 페이지**: UI 디자인 및 문구 작성


### **유영훈**
#### **프론트엔드**
- **분실물/습득물 게시판**: 게시글 목록 및 검색 결과 페이지 구현
- **쪽지 페이지**: 쪽지 목록, 쪽지 보내기, 확인 페이지
- **마이페이지 및 관리자 페이지**: 디자인 및 UI 구현
- **게시글 페이지**: 글쓰기 및 상세 보기 페이지


### **노광우**
#### **백엔드**
- **메인 페이지**: 데이터 연동 및 게시판 구현
- **검색 기능**: 분실물/습득물 게시판 정렬(최신순/오래된 순)
- **비밀번호 찾기 페이지**: 이메일을 통한 임시 비밀번호 발급

#### **조장 역할**
- **프로젝트 관리 및 서류 작성**


### **김혜림 (본인)**
#### **DB 테이블 설계**
#### **백엔드**
- **마이페이지**: 회원 정보 수정, 쪽지 확인, 작성한 게시글 관리
- **글쓰기 페이지**: 물품 선택, 위치 검색, 이미지 등록
- **쪽지 시스템**: 받은/보낸 쪽지 관리, 답장, 새로운 쪽지 알림
- **비밀번호 찾기 기능**: 아이디 입력 후 이메일 발급

#### **프론트엔드**
- **메인 페이지, 로그인/회원가입 페이지**: UI 디자인 및 문구 작성

---

## **개발 환경 및 주요 기술 스택**
- **프레임워크**: Spring Boot (Maven 기반)
- **백엔드**: JPA, JDBC, Thymeleaf, Lombok, Mail (SMTP)
- **데이터베이스**: MySQL
- **프론트엔드**: HTML, CSS, JavaScript, Thymeleaf
- **기타 도구**: Git, FileZilla


## **프로젝트 목표**
1. **분실물 찾기 성공률 향상**  
   사용자들이 분실한 물건을 쉽게 찾도록 도움.  
2. **사회적 문제 해결**  
   분실물 및 습득물 관리 문제를 해결하여 사회에 기여.  
3. **신뢰와 커뮤니티 형성**  
   사용자 간 신뢰 기반 소통 채널 제공.  
4. **사용자 친화적 UI/UX 제공**  
   직관적이고 사용하기 쉬운 웹 디자인 구현.  


## **요구사항 분석**
- **회원가입 및 로그인**: 인증된 사용자만 플랫폼 이용 가능.
- **게시글 작성/관리**: 게시글 작성, 수정, 삭제 가능.
- **댓글 기능**: 게시글 상호작용 유도.
- **쪽지 기능**: 사용자 간 비공식적 소통 지원.
- **비밀번호 찾기**: 이메일을 통한 비밀번호 재설정 기능.


## **시스템 아키텍처**
- **Controller**, **Service**, **DAO**로 계층화된 구조.  
- 템플릿 엔진인 **Thymeleaf**로 UI와 데이터 연동.  
- **MySQL**로 데이터를 관리하며, **Spring Mail**로 이메일 서비스 구현.  


## **프로젝트 구조**

src
├── main
│   ├── java
│   │   └── com
│   │       └── project
│   │           └── sprint1
│   │               ├── controller
│   │               │   ├── AdminController.java
│   │               │   ├── BoardController.java
│   │               │   ├── MainController.java
│   │               │   ├── MessageController.java
│   │               │   ├── MypageController.java
│   │               │   ├── PasswordController.java
│   │               │   └── UserController.java
│   │               ├── dao
│   │               │   ├── AdminDao.java
│   │               │   ├── BoardDao.java
│   │               │   ├── MainDao.java
│   │               │   ├── MessageDao.java
│   │               │   ├── MypageDao.java
│   │               │   ├── PasswordDao.java
│   │               │   ├── PostDao.java
│   │               │   └── UserDao.java
│   │               ├── service
│   │               │   └── EmailService.java
│   │               └── Sprint1Application.java
│   └── resources
│       ├── static
│       │   ├── css
│       │   └── img
│       ├── js
│       └── templates
│           ├── board
│           │   ├── category.html
│           │   ├── detail.html
│           │   ├── insert.html
│           │   └── location.html
│           ├── menu
│           │   ├── finditem.html
│           │   ├── lostitem.html
│           │   ├── searchfi.html
│           │   └── searchli.html
│           ├── message
│           │   └── message_insert.html
│           │   └── message_notice.html
│           │   └── message.html
│           ├── adminpage.html
│           ├── find-password.html
│           ├── login.html
│           ├── main.html
│           ├── mypage.html
│           ├── password.html
│           └── signup.html
│       └── application.properties

src
├── main
│   ├── java
│   │   └── com
│   │       └── project
│   │           └── sprint1
│   │               ├── controller
│   │               │   ├── AdminController.java        # 관리자 관련 기능 컨트롤러
│   │               │   ├── BoardController.java        # 게시판 관련 기능 컨트롤러
│   │               │   ├── MainController.java         # 메인 페이지 관련 컨트롤러
│   │               │   ├── MessageController.java      # 쪽지 관련 기능 컨트롤러
│   │               │   ├── MypageController.java       # 마이페이지 관련 컨트롤러
│   │               │   ├── PasswordController.java     # 비밀번호 찾기 관련 컨트롤러
│   │               │   └── UserController.java         # 사용자 관리 기능 컨트롤러
│   │               ├── dao
│   │               │   ├── AdminDao.java               # 관리자 데이터 접근 객체
│   │               │   ├── BoardDao.java               # 게시판 데이터 접근 객체
│   │               │   ├── MainDao.java                # 메인 페이지 데이터 접근 객체
│   │               │   ├── MessageDao.java             # 쪽지 데이터 접근 객체
│   │               │   ├── MypageDao.java              # 마이페이지 데이터 접근 객체
│   │               │   ├── PasswordDao.java            # 비밀번호 찾기 데이터 접근 객체
│   │               │   ├── PostDao.java                # 게시글 데이터 접근 객체
│   │               │   └── UserDao.java                # 사용자 데이터 접근 객체
│   │               ├── service
│   │               │   └── EmailService.java           # 이메일 관련 서비스
│   │               └── Sprint1Application.java         # Spring Boot 메인 애플리케이션
│   └── resources
│       ├── static
│       │   ├── css                                     # CSS 파일 디렉터리
│       │   └── img                                     # 이미지 파일 디렉터리
│       ├── js                                          # JavaScript 파일 디렉터리
│       └── templates                                   # Thymeleaf 템플릿 디렉터리
│           ├── board
│           │   ├── category.html                       # 게시판 카테고리 템플릿
│           │   ├── detail.html                         # 게시판 상세 보기 템플릿
│           │   ├── insert.html                         # 게시글 작성 템플릿
│           │   └── location.html                       # 위치 검색 템플릿
│           ├── menu
│           │   ├── finditem.html                       # 습득물 게시판 템플릿
│           │   ├── lostitem.html                       # 분실물 게시판 템플릿
│           │   ├── searchfi.html                       # 습득물 검색 결과 템플릿
│           │   └── searchli.html                       # 분실물 검색 결과 템플릿
│           ├── message
│           │   ├── message_insert.html                 # 쪽지 작성 템플릿
│           │   ├── message_notice.html                 # 쪽지 알림 템플릿
│           │   └── message.html                        # 쪽지 확인 템플릿
│           ├── adminpage.html                          # 관리자 페이지 템플릿
│           ├── find-password.html                      # 비밀번호 찾기 템플릿
│           ├── login.html                              # 로그인 페이지 템플릿
│           ├── main.html                               # 메인 페이지 템플릿
│           ├── mypage.html                             # 마이페이지 템플릿
│           ├── password.html                           # 비밀번호 변경 템플릿
│           └── signup.html                             # 회원가입 페이지 템플릿
│       └── application.properties                      # 애플리케이션 설정 파일



## **주요 기능**
1. **회원가입 및 로그인**: 인증된 사용자만 이용 가능.
2. **게시판 기능**: 분실물/습득물 등록, 검색, 상태 관리.
3. **쪽지 기능**: 비공식적 사용자 간 소통.
4. **관리자 페이지**: 회원 및 게시글 관리.


## **참고 사이트**
- [Lost112](http://www.lost112.go.kr) - 국가 분실물 종합 관리 시스템
