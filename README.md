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
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_쪽지확인.jpeg)<br>
![Pynk](https://raw.githubusercontent.com/khr316/lost-find/main/웹사이트/pynk_쪽지확인2.jpeg)<br>
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
