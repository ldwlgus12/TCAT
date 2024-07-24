# TCAT

#### 🎫 django를 이용한 나만의 티켓 기록 사이트

##### 멀티캠퍼스 풀스택 개발자 취업캠프 - 최종 프로젝트 
- 프로젝트 기간: 2023. 05. 22 ~ 2023. 06. 16
- 참여 인원: 4명 (도용주, 변지윤, 서현석, 전지현)

##### 개발 환경
- Python
- Django
- HTML/CSS/JavaScript
- Bootstrap
- Social Login API

##### 구현 기능
- `회원가입/로그인/회원탈퇴`
  - 회원가입 시 (필수)가 적혀 있는 사항은 반드시 체크해야 회원가입 가능
  - reCAPTCHA 를 활용한 보안 이미지 생성
  - 로그인 시 유효성 체크 (아이디 또는 비밀번호가 올바르지 않습니다.)

- `메인 페이지`
  - 나의 캘린더에서 캘린더 캡쳐 버튼을 누르면 캘린더가 자동으로 캡쳐되어 저장됨
  - 이미 생성된 기록은 드래그 앤 드랍으로 날짜 변경 가능
  - 유저가 작성한 데이터를 토대로 그래프 출력
  - 현재 인터파크에서 인기있는 티켓을 카테고리 별로 확인 가능
  - 기록 모아보기 버튼을 클릭하면 유저가 현재까지 작성한 기록을 한 번에 볼 수 있음

- `챗 봇`
  - 화면 오른쪽 하단에 버튼을 클릭하여 운영자와 상담 가능

- `기록 생성`
  - 나의 캘린더에서 날짜를 클릭하거나 기록 생성하기 버튼으로 기록을 생성할 수 있음

- `프로필 페이지`
  - 내가 작성한 기록에 따라 레벨이 변하는 레벨 시스템
  - 다른 유저와 맞팔로우시 상대방의 캘린더로 이동 가능

- `검색 기능`
  - 상단 검색창을 이용해 내가 작성한 기록, 다른 유저 아이디, 다른 유저가 작성한 기록 검색 가능

##### base code
- project 생성
- accounts app 생성 및 project url과 연결
- accounts에서 기본 django 내장 django.contrib.auth 모델을 만질 수 있게 모델 대치
- .gitignore 생성
- django, pillow, imagekit
- 위에 필요한 settings.py 조정
- templates 폴더 생성, settings.py base templates 폴더 연결
- base.html 생성 및 bootstrap 적용
- LANGUAGE_CODE, TIME_ZONE 한국으로 설정

##### 참고
- 초기 디자인 설계: [figma](https://www.figma.com/design/XhYhMthSg2JFFfw0H4dslV/TCAT---design?node-id=0-1)
