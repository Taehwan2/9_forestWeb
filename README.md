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
<img src="https://img.shields.io/badge/JSP-F7DF1E?style=for-the-badge&logo=jsp&logoColor=white">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL-4479A1&logoColor=white">

#### FrontEnd
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">


### Communicatoin
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"><img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"><img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white">

## 프로젝트 진행 과정
- 피그마를 이용해 목업 디자인 스케치와 메인 디자인 
- 페이지 별 역할 분담
- 기능 구현
- 배포 테스트 및 기능 수정
- 배포

## 프로젝트 구현 내용
<img width="959" alt="스크린샷 2023-08-20 오후 11 35 24" src="https://github.com/Taehwan2/9_forestWeb/assets/97010824/8f0756cf-474d-4e58-8983-30885d2cac64">

1. JSON으로 사용자의 정보를 받아온 후 회원가입을 하고, 로그인을 하는 기능을 구현,

<img width="1158" alt="스크린샷 2023-08-20 오후 11 35 44" src="https://github.com/Taehwan2/9_forestWeb/assets/97010824/7654ce17-a469-4b24-9723-a4d41a512aa8">

2. 배달주문을 누를 시 COUNT를 증가시켜 몇 회 이상 주문시 알람을 주는 기능을 구현

## 프로젝트 한계 및 개선 방안
1. JSP에 모든 코드와 기능을 넣다보니 가독성이 너무 떨어짐 -> 추후 SPRING을 공부하는 계기가 되었다.
2. 결제기능을 구현하기 불가했다. -> Mock 데이터로 처리했다.
3. front를 다룰 수 있는 인원이 없어서 -> 역할을 분담하여 bootstrap을 사용해서 빠르게 front를 작성했다.

