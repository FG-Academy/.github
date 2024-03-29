# 꽃동산 아카데미 외주개발 프로젝트 향후 진행상황



## 3월 19일 ~ 3월 31일까지 진행해야하는 부분들



### 퀴즈 관련 기능

- 퀴즈 페이지(FE)
  - 브라우저에서 사용자가 퀴즈를 풀 수 있는 기능 구현
  - 퀴즈 제출 후 제출 완료 및 채점 결과를 브라우저에서 확인할 수 있는 기능 구현
- 퀴즈 등록
  - 관리자가 퀴즈를 등록할 수 있는 기능(간혹 설문을 진행한다고도 하니, 퀴즈 타입에 따라 제출 Validation 을 잘 고려해야할 듯)
- 퀴즈 제출
  - 사용자가 퀴즈를 제출하고 DB에 저장하는 기능
- 퀴즈 채점
  - 사용자가 제출한 퀴즈와 미리 입력된 정답을 대조해서 사용자의 퀴즈가 정답인지 아닌지 유무를 파악하는 기능
- 퀴즈 관리
  - ~~사용자관점) 사용자가 제출한 퀴즈를 확인할 수 있는 기능 및 페이지~~
  - 관리자관점) 사용자들이 제출한 퀴즈를 종합적으로 검토할 수 있는 기능 및 페이지



### 내 강의실 기능

- 현재 내가 수강중인 강의 페이지(FE)
  - 사용자가 현재 수강 중인 코스 정보를 보여준다. 
- 내가 제출한 퀴즈 열람(FE)
  - 사용자가 제출한 퀴즈 정보를 가져온다
- 수강 중인 코스 정보 가져오기(BE)
  - 사용자가 수강 중인 코스의 세부 정보를 API를 통해 가져온다. 
- 제출한 퀴즈 정보 가져오기(BE)
  - 사용자가 제출한 퀴즈 정보를 API를 통해 가져온다
- 사용자 이름 및 정보 표기(FE)
  - 이름, 레벨, 부서 등



### 비밀번호 찾기

- 비밀번호 찾기 페이지 구현
  - 사용자의 아이디와 이메일 정보를 입력하면 이메일로 인증 정보를 보낸다.
  - 인증을 통과한 사용자는 비밀번호를 재설정한다.



### 로그인 관련

- 로그인 시에 헤더가 제대로 표기 되지 않는 문제 해결
- Local storage를 사용하는 방식이 아닌 NextJS의 인증 방식을 도입해서 로그인 안정성을 높여야한다.



### 관리자 페이지

- 관리자 페이지를 디자인하고 기능을 구현해야한다.



### 배포용 서버 미리 구축

- 클라이언트 측에서 진행상황을 지속적으로 확인할 수 있도록 배포용 서버를 구축해서 배포한다.
- 해당 서버는 프로젝트 완료 후 실제 사용자들에게 공개될 배포용 서버로 사용한다.
