# 9_forestWeb
# 숲웹🏕️

## 프로젝트 
### 개요
- "스마트 배달 제한 시스템"은 사용자의 건강을 보호하기 위해 일정 횟수 이상의 배달음식 주문이 이루어질 경우 자동으로 차단하는 웹 서비스입니다.
- 사용자가 설정한 주문 횟수 한도에 도달하면, 시스템은 자동으로 배달 음식 주문을 제한하며, 대신 건강한 식단 선택에 도움이 될 수 있는 정보를 제공합니다.
- 내가 사용한 소비내역 입력을 통한 지출계획을 한눈에 보는 서비스 구축

### 배경

## 개발인원(Member)
|이름|역할|담당|이름|역할|담당|
|--|--|--|--|--|--|
|장태환|BE 팀장| JSP,MYSQL |신현빈|BE| ERD |
|손지석|FE 팀원| HTML |
|남혁준|FE 팀원| JS |

## 프로젝트 기술 스택
### Environments
[![Eclipse](https://img.shields.io/badge/eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white)](https://www.eclipse.org/)
[![MySQL](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
<img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"><img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">

### Development Stack
#### BackEnd



#### FrontEnd


### Communicatoin
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"><img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"><img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white">

## 프로젝트 진행 과정
- 피그마를 이용해 목업 디자인 스케치와 메인 디자인 
- 페이지 별 역할 분담
- 기능 구현
- 배포 테스트 및 기능 수정
- 배포

## 프로젝트 구현 내용
### FE
#### 정지은
#### 1. 소비페이지 /일일
<p align="center">
<img width="606" alt="스크린샷 2023-08-03 오후 7 02 00" src="https://github.com/codestates-seb/seb44_main_010/assets/112951633/da47c46a-17b3-4b4a-9013-5efe0e0448b9">
</p>

- 기존에 있는 계좌와 추가된 현금거래 데이터를 서로 같은 형식으로 렌더링함. 추가하기 버튼을 누르면 현금거래 내역을 추가할 수 있음.



#### 2. 소비페이지 /월별
<p align="center">
<img width="601" alt="스크린샷 2023-08-03 오후 7 02 31" src="https://github.com/codestates-seb/seb44_main_010/assets/112951633/21bd76de-8261-45ab-8946-09af13a08faf">
</p>

- 계좌와 현금 일일 데이터를 date, data 라는 각각의 속성을 새로 부여하여 데이터 처리함. 서버에서 받아온 계좌와 현금의 데이터 구성이 서로 달랐기 때문에, 새로운 배열을 만듦.



#### 3. 소비페이지 /달력
<p align="center">
<img width="601" alt="스크린샷 2023-08-03 오후 7 02 44" src="https://github.com/codestates-seb/seb44_main_010/assets/112951633/330529c0-4f7d-41ae-bc9a-9c85eb3b6cc3">
</p>

- 1월 ~ 12월 달력을 만들고, 입금/출금을 렌더링함



#### 4. 소비페이지 /요약
<p align="center">
<img width="604" alt="스크린샷 2023-08-03 오후 7 02 54" src="https://github.com/codestates-seb/seb44_main_010/assets/112951633/ad0359a0-b380-4828-b78b-5e51d58d9e24">
</p>

- chart.js 라는 외부 라이브러리를 사용하여 카테고리별 통계 자료를 보여줌. 


#### 정태현

#### 채명수
#### 1. 회원가입 페이지
<p align="center">
<img width="70%" alt="스크린샷 2023-08-02 오후 3 50 17" src="https://github.com/codestates-seb/seb44_main_010/assets/124559717/184288b6-fbdb-44d0-a8c5-e7f79494616c"> 
</p>

- 회원가입시 사용되는 메일을 통해 [**이메일 인증하기**](https://velog.io/@coaudtn0276/Project-%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85-%EB%A9%94%EC%9D%BC-%EC%9D%B8%EC%A6%9D-%EA%B8%B0%EB%8A%A5%EA%B5%AC%ED%98%84) 버튼을 누르면 메일을 통해 인증번호 전송.

<p align="center">
<img width="70%" alt="스크린샷 2023-08-02 오후 3 50 17" src="https://github.com/codestates-seb/seb44_main_010/assets/124559717/f85b3fbf-790a-4885-87d5-adf7d7974579"> 
</p>

- 알맞은 메일주소와 메일을 통해 받은 인증번호를 알맞게 넣으면 가입 완료버튼 활성화

#### 2. 로그인 페이지
<p align="center">
<img width="70%" alt="스크린샷 2023-08-02 오후 3 50 17" src="https://github.com/codestates-seb/seb44_main_010/assets/124559717/4a4e5fad-d21c-462a-b0fc-50f8aca76946"> 
</p>

- 회원가입이된 아이디와 비밀번호, [**reCAPTCHA 인증**](https://velog.io/@coaudtn0276/ProjectReact%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%9C-google-reCAPTCHA) 까지 확인이 되면 로그인버튼이 나오면서 로그인이 가능하게 구현

<p align="center">
<img width="70%" alt="스크린샷 2023-08-02 오후 3 50 17" src="https://github.com/codestates-seb/seb44_main_010/assets/124559717/6bc9f123-0af3-4b32-9a08-0bfae0a116c1"> 
</p>

- 로그인 완료 후 Local Storage를 통해 발급받은 [**토큰**](https://velog.io/@coaudtn0276/Project-%ED%86%A0%ED%81%B0%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EB%A1%9C%EA%B7%B8%EC%9D%B8-%EA%B8%B0%EB%8A%A5-%EA%B5%AC%ED%98%84), 이름, userId를 저장하고 React-toolkit을 이용해 로그인 상태의 유무 확인

#### 3. 서버로부터 받은 Profile데이터 Redux-toolkit으로 저장 후 사용
<p align="center">
<img width="30%" alt="스크린샷 2023-08-02 오후 3 50 17" src="https://github.com/codestates-seb/seb44_main_010/assets/124559717/26468ad1-cd32-4083-a83f-8ad44dbb10ea"> 
</p>

- Profile 컴포넌트의 경우 서비스하는 페이지마다 들어가야하는 데이터였기 때문에 [**Redux-toolkit**](https://velog.io/@coaudtn0276/Project-Redux%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%9C-api%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%A0%80%EC%9E%A5) 으로 저장 후 사용

#### 4. 챗봇 UI
<p align="center">
<img width="30%" alt="스크린샷 2023-08-02 오후 3 50 17" src="https://github.com/codestates-seb/seb44_main_010/assets/124559717/fde30c45-2efc-4f84-9895-54a19b7e973c"> 
</p>

- Dialogflow로 만들어진 서버와 통신 후, 질문에 대한 답변 데이터를 챗봇에 구현

  
### BE
#### 이은호

#### 백지희

#### 장태환
## 프로젝트 한계 및 개선 방안
### FE
#### 한계
- 프로젝트 초기 단계에서 웹과 앱을 동시에 구현하기 위해 PWA 셋팅을 하였지만 후반으로 갈 수록 PWA에 관해서는 다뤄보지 못함.
프로젝트를 반응형으로 만들면 간단하게 해결될 문제일 줄 알았는데 반응형을 좀 더 정교하게 만들었어야 했다는 생각이 듦.
- 메인페이지 섹션별 스크롤 이벤트를 구현 하였는데 마우스 휠로는 구현이 잘 됬지만 트랙패드의 경우 버벅거리는 에러를 발견.
- 일일 페이지에서 일이동 여러번 클릭해야 원하는 날짜로 이동할 수 있음
- 현금 자산을 등록해야, 일일 소비내역을 입력할 수 있도록 알림창을 띄워놓았는데, 알림창이 아닌 아예 논클릭으로 실행불가능하도록 구현해야 함

#### 개선 방안
- 모바일까지 생각한 반응형 웹의 경우 최소 크기에서부터 컴포넌트들을 배치 하면서 점점 페이지 크기를 키워가면서 구현.
- 일일 페이지에서 단순히 일이동 버튼을 눌러서 +1,-1 로 이동하는 것이 아니라, 특정 날짜를 입력할 수 있다면, 사용자가 편리할 것이라고 생각함.
- 기존 현금자산보다 더 높은 금액을 input 창에 입력하면, 등록버튼을 눌러도 화면이 넘어가지 않도록 구현.
  
### BE

