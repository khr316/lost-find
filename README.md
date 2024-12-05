# 분실물&습득물 찾기 웹 서비스 플랫폼 제작<br>(Lost and Found Platform)


## [프로젝트 확인](https://khr316.tistory.com/entry/KEPCO-luckyPYNK-sprint)
<br><br>



### 로그인 전 메인페이지
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_main.jpeg)
간단한 사이트 이용 정보 확인
<br><br>

### 회원가입
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_회원가입.jpeg)
1. 아이디 중복체크 필수
2. 비밀번호 = 비밀번호확인
3. 모든 칸 입력 필수
<br><br>

### 로그인
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_로그인.jpeg)
모든 칸 입력 필수
<br><br>

### 비밀번호 찾기
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_비번찾기.jpeg)<br>
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_메일.PNG)<br>
가입한 아이디와 이메일 정보를 통해 임시비밀번호 발급
<br><br>

### 로그인 후 메인페이지
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_main로그인.jpeg)
메뉴 상단바 변화
<br><br>

### 마이페이지
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_마이페이지.jpeg)
1. 개인정보 확인 및 수정 가능
2. 쪽지 확인 버튼 옆 알림 기능
3. 작성한 글 확인
   분실물 상태 변경 기능 (찾는중 -> 찾기완료)
4. 탈퇴 -> DB에 저장된 회원 정보 삭제됨
<br><br>

### 글쓰기
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_글쓰기.jpeg)
1. 분실물 or 습득물 등록 선택
2. 위치 선택 후 상세 위치 입력
3. 이미지 파일 미등록시 기본 이미지로 등록됨
4. 등록 물품 카테고리 선택 후 상세 카테고리 선택 가능
<br><br>

### 게시판
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_게시판1.jpeg)<br>
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_게시판2.jpeg)<br>
1. 우측 상단 버튼을 통해 분실물, 습득물 게시판 자유롭게 이동 가능
2. 제목 키워드 검색 기능
3. 검색창 우측 select 를 통해 지역별 검색 가능
4. 게시글 등록 최신순, 오래된순 조회 가능
<br><br>

### 게시글
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_게시글.jpeg)
1. 본인인 경우 게시글 수정 및 삭제 가능
2. 댓글 기능 - 본인인 경우 수정 및 삭제 가능
3. 작성자에게 다이렉트 쪽지 보내기 가능
<br><br>

### 쪽지 페이지
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_쪽지2.jpeg)
1. 사이트에 가입한 회원들에게 쪽지 보내기 가능 (관리자 아이디는 표시 X)
2. 미확인 쪽지 알림 기능
<br><br>

### 쪽지 확인
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_쪽지확인.PNG)<br>
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_쪽지확인2.PNG)<br>
보낸 쪽지, 받은 쪽지 확인 및 답장
<br><br>

### 쪽지 보내기
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_쪽지답장.jpeg)
보내는 이와 받는 이 아이디 확인 가능
<br><br>

### 관리자
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_main관리자.jpeg)<br>
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_관리자페이지.jpeg)<br>
1. 메뉴 상단바 관리자페이지
2. 가입한 회원 정보 확인 및 탈퇴 시키기
3. 등록된 게시글 관리 가능 (수정 및 삭제)
<br><br>


#### 시스템
![ERD](https://raw.githubusercontent.com/khr316/lost-find/main/데이터베이스설계.png)<br>
![아키텍처](https://raw.githubusercontent.com/khr316/lost-find/main/시스템구조.jpeg)<br>




luckyPYNK - 분실물 습득물 관리 웹 플랫폼


프로젝트 개요
luckyPYNK은 분실물 및 습득물을 관리할 수 있는 웹 플랫폼입니다.
게시판 형식으로 운영되며, 회원 가입 후 분실물/습득물 정보를 등록, 검색, 관리할 수 있습니다.
회원 간 쪽지 기능을 통해 소통을 지원하며, 사용 친화적이고 직관적인 UI/UX를 제공합니다.



프로젝트 기간: 2024.07.04 ~ 2024.07.15 (2주)
팀 구성: 4명
박소라, 유영훈, 노광우, 김혜림(본인)
역할 분담
박소라:
백엔드:
회원가입 페이지 구현 (아이디 중복 체크, 필수 입력사항 처리, 비밀번호 확인 일치 등)
로그인 페이지 구현 (DB에 저장된 회원만 로그인 가능, 오류 메시지 처리)
관리자 페이지 구현 (회원 탈퇴, 게시글 및 댓글 삭제)
게시글 페이지 (글 작성자 수정/삭제, 관리자 삭제 등 기능)
프론트엔드:
메인 페이지, 로그인 페이지, 회원가입 페이지 디자인 및 문구 작성
유영훈:
프론트엔드:
분실물 게시판, 습득물 게시판, 검색 결과 페이지 구현
쪽지 관련 페이지 (쪽지 목록, 쪽지 보내기, 쪽지 확인 페이지 등)
마이페이지 및 관리자 페이지 디자인 및 구현
글쓰기 페이지, 게시글 페이지 구현
노광우:
백엔드:
메인페이지, 분실물 및 습득물 게시판 페이지 구현
분실물 및 습득물 검색 기능 구현 (최신순, 오래된 순)
비밀번호 찾기 페이지 개선 (이메일을 통한 임시 비밀번호 발급)
조장:
프로젝트 관리 및 서류 작성
김혜림:
백엔드:
마이페이지 (회원 정보 수정, 쪽지 확인, 작성한 게시글 관리)
글쓰기 페이지 (물품 선택, 위치 검색, 이미지 등록 기능)
쪽지 시스템 (받은/보낸 쪽지 확인, 답장, 새로운 쪽지 알림)
비밀번호 찾기 기능 구현 (아이디 입력 시 비밀번호 발급)
프론트엔드:
메인페이지, 로그인 페이지, 회원가입 페이지 디자인 및 문구 작성

개발 환경 및 주요 기술 스택
프레임워크: Spring Boot (Maven 기반)
백엔드: JPA, JDBC, Thymeleaf, Lombok, Mail (SMTP)
데이터베이스: MySQL
프론트엔드: HTML, CSS, JavaScript, Thymeleaf
기타 도구: Git, FileZilla

프로젝트 목표
분실물 찾기 성공률 향상: 사용자가 분실한 물건을 쉽게 찾을 수 있도록 돕는 웹 플랫폼 제공.
사회적 문제 해결: 분실물 및 습득물 관리에 있어 사회적인 기여.
신뢰와 커뮤니티 형성: 사용자 간 신뢰를 기반으로 한 소통 채널 제공.
사용자 친화적 UI/UX: 직관적이고 사용하기 쉬운 웹 디자인 제공.
요구사항 분석
회원가입 및 로그인: 회원 가입과 로그인을 통해 인증된 사용자만 플랫폼을 이용할 수 있도록 구현.
게시글 작성 및 관리: 분실물 및 습득물 게시판에서 게시글을 작성하고 수정, 삭제할 수 있는 기능 구현.
댓글 기능: 각 게시글에 댓글을 작성하여 사용자 간 상호작용을 유도.
쪽지 기능: 사용자 간 비공식적인 소통을 위한 쪽지 시스템 구현.
비밀번호 찾기 기능: 이메일을 통한 비밀번호 재설정 기능.
ERD (Entity Relationship Diagram)





시스템 아키텍처

주요 기능
회원가입 및 로그인: 사용자만 이용할 수 있도록 회원가입 및 로그인 기능을 제공.
분실물/습득물 게시판: 사용자가 분실물 또는 습득물을 게시하고 검색할 수 있도록 구현.
분실물 상태 관리: 게시글에 상태를 설정하여 '찾는 중' 또는 '찾기 완료'로 관리.
쪽지 기능: 사용자 간에 쪽지를 보내고 받을 수 있도록 하는 비공식적인 소통 기능.
관리자 페이지: 관리자가 회원 탈퇴 및 게시글, 댓글 삭제 등을 관리할 수 있는 기능 제공.

프로젝트 구조
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




참고 사이트 : 
Lost112 - 국가 분실물 종합 관리 시스템





코드 :

https://github.com/khr316/lost-find
