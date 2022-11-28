# ![favicon-32x32](https://user-images.githubusercontent.com/119276371/204209638-9e5b1b62-da07-4533-959d-c4771c5d8fca.png) GGANBU.GG (깐부.GG)
빅데이터를 활용한 롤 챔피언 추천

<br/>

## 🧑팀원 소개

|<center>최진욱(팀장)</center>|<center>남현우</center>|<center>강석민</center>|<center>최영선</center>|<center>김지수</center>|<center>박무창</center>|
|:---:|:---:|:---:|:---:|:---:|:---:|
|<center>BACKEND</center>|<center>BACKEND</center>|<center>BACKEND</center>|<center>FRONTEND</center>|<center>FRONTEND</center>|<center>FRONTEND</center>|



<br/><br/><br/>
## 🧭Git 컨벤션 개요
Conflict를 방지하고, 효과적이고 명확한 협업을 진행하고자 Git-Flow 브랜치 전략을 도입하여 계층별 브랜치를 관리했습니다.

### Git Flow
```
master   
└ develop  
  ├ front - feature/FE-기능...  
  └ back - feature/BE-기능...
```
  
master : 운영 서버로 배포하기 위한 브랜치

develop : 다음 출시 기능을 개발하는 브랜치

frontend : 프론트엔드 개발하는 브랜치

backend : 백엔드를 개발하는 브랜치

feature : 세부 기능을 개발하는 브랜치

`feature-` 이후에 어떤 기능을 개발하는지를 붙여주었습니다.


<br/><br/><br/>

## 🖥프로젝트
<div align=center><h3>📚 STACKS</h3></div>

<div align=center>
<img src="https://img.shields.io/badge/openjdk-007396?style=for-the-badge&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<br>
<img src="https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
<img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black">
<img src="https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">  
<img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">  
<img src="https://img.shields.io/badge/jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white">  
<br> 
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">       
  <img src="https://img.shields.io/badge/next.js-61DAFB?style=for-the-badge&logo=next.js&logoColor=black"> 
  <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
<br>
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
</div>

<br/><br/><br/>

### 개발 환경
- **Frontend** (프론트에서 보고 고쳐주셈)
  - HTML5, CSS3, JS(ES6)
  - Next.js
  - Visual Studio Code
  
  <br/>

- **Backend**
  - Java
  - Hadoop MapReduce
  - Spring Boot, Spring MVC
  - Spring Data MongoDB
  - Gradle
  - MongoDB
  - Intellij

  <br/>
  
- **DevOps**
  - AWS EC2
  - Apache Tomcat
  - Docker
  - Jenkins

  <br/>

- **Collaboration**
  - Jira
  - Gitlab
  - Mattermost
  - [Notion](https://evergreen-tea-82e.notion.site/ad5b30ce5f15442ca84d643f8bd051c8?v=d631430ed9734878b7d90dd0d9485c54)

<br/><br/><br/>

### 프로젝트 개요
- **진행기간**
  - 2022.08.22 ~ 2022.10.07 (6주)

<br/>

- **목표**
    - 

<br/>

- **와이어프레임**(figma)

![KakaoTalk_20221007_180853053](https://user-images.githubusercontent.com/119276371/204209709-cc074560-3637-4dc4-8d17-d5aac41680c5.png)


<br/>

- **ERD**



<br/>

- **화면정의서**


<br/>



<br/>

- **시퀀스 다이어그램**




<br/><br/><br/>

## 📖프로젝트 소개

### 기획 배경

1. 최근 방송인들의 수가 늘어가면서 게임에 대해 관심을 가지게 되는 사람들이 급증하는 추세입니다.
2. 그 중 '리그 오브 레전드'라는 게임은 타 게임에 비해 해당 게임을 알고 있는 사람의 수가 매우 많습니다.
3. 하지만 게임의 복잡한 특성상 쉽게 접하기 어렵고, 이미 플레이 중인 유저도 게임의 방대한 데이터를 전부 알고 있기 어렵습니다.



### 기획 의도

'리그 오브 레전드' 라는 게임을 플레이하고 있는 유저의 경우 해당 게임에 대한 방대한 정보를 쉽게 얻을 수 있을 뿐만 아니라
게임에 대한 숙련도를 높이기 위한 정보를 빠르게 찾고 자신의 게임 플레이 스타일에 적용할 수 있도록 합니다.
그리고 '리그 오브 레전드'를 해보지 않는 사람들 중에 해당 게임에 관심이 생겼거나 다른 이들에게 추천을 받게 되었을 경우
해당 게임의 컨셉을 좀 더 쉽게 이해하고 경험해볼 수 있는 기회를 제공하고자 합니다.


### 대상 사용자

1. 게임은 안하지만 게임에 대한 전반적인 정보가 필요한 사람
2. 게임에 이제 막 관심을 가져보려고 생각중인 사람
3. 이미 해당 게임을 진행하고 있던 사람
4. 다른 사람에게 이 게임을 추천해주고 싶은 사람
5. 게임을 위해서 머리 아프게 정보를 다 외우고 싶진 않은 사람
6. 해당 게임에 대해서 처음 알게 된 사람

### 기대 효과

1. 해외 유명 게임인 '리그 오브 레전드'를 플레이하는 유저들에게 있어 우리팀에 잘 맞는 캐릭터가 무엇인지 빠르고 정확하게 알 수 있습니다.
2. '리그 오브 레전드'에는 161개의 캐릭터가 있기 때문에 각 캐릭터들에 대한 정보를 한 눈에 보기 쉽게 정리되어 빠르게 정보를 수집할 수 있습니다.
3. '리그 오브 레전드'를 플레이하는 유저를 비롯하여 해당 게임을 아직 접해보지 못한 사람들에게 게임에 대한 이해와 친숙함을 빠르게 높혀 줄 수 있습니다. 


<br/><br/><br/>

## 📌주요 기능

### 홈페이지
![홈화면-블랙](https://user-images.githubusercontent.com/119276371/204209808-d231373e-9b2e-4477-b588-9414d6c7cd5e.png)
![홈화면-화이트](https://user-images.githubusercontent.com/119276371/204209817-46a27678-f92d-4db8-b152-51d480b61d94.png)


### 챔피언 추천
![챔피언추천-깐부](https://user-images.githubusercontent.com/119276371/204209844-72a5f72b-a89c-4c83-9c5e-cd636d683564.png)
![챔피언추천-전체](https://user-images.githubusercontent.com/119276371/204209855-4700b21b-7357-4961-a1a3-23d86a012697.png)
![추천결괴-1](https://user-images.githubusercontent.com/119276371/204209870-8fffda35-0e84-49e6-b302-680bb4025271.png)
![추천결과-2](https://user-images.githubusercontent.com/119276371/204209876-c8c9dae8-8094-4115-96e7-9b65948ef02d.png)


#### 챔피언 보기
![챔피언보기](https://user-images.githubusercontent.com/119276371/204209900-244fec37-bf67-48d0-9dd9-d8ce50ff3b66.png)
![챔피언보기-단어구름](https://user-images.githubusercontent.com/119276371/204209910-292d8f98-8ff7-4888-8168-323c8b93adbf.png)


### 게임
#### 지역찾기
![지역찾기](https://user-images.githubusercontent.com/119276371/204209932-3aef1e4e-d708-4719-a4ea-37a09a92f68b.png)

#### 스킬 맞추기
![스킬맞추기](https://user-images.githubusercontent.com/119276371/204209957-ec1c7f9e-5a99-4247-92e9-9acf8a289278.png)

#### 말파이트 궁피하기
![궁피하기](https://user-images.githubusercontent.com/119276371/204209991-c638e9ae-2c68-4d99-a931-8d241eee8883.png)


### 이상형 월드컵
![이상형월드컵](https://user-images.githubusercontent.com/119276371/204210007-a669b4f8-62ea-4d43-b1d0-087780421d82.png)
![이상형월드컵-결과](https://user-images.githubusercontent.com/119276371/204210014-ea3096cb-d094-4dcd-a61c-f1dd33658b90.png)


### 노래
![음악](https://user-images.githubusercontent.com/119276371/204210027-d40635c8-80b5-4983-bf07-021b14a0866c.png)



<br/><br/><br/>

## 📃설치 및 실행 가이드
도커 젠킨스 CI/CD 관련 설명

- Frontend
```
$ cd frontend
$ npm i
$ npm run build
$ npm run start
```
- Backend
```
# API server 
$ cd backend
$ gradle wrap # gradle wrapper 없을 경우 실행
$ ./gradlew clean build
$ sudo java -jar "/home/ubuntu/S07P12C111/backend-java/ssafy-web-project-1.0-SNAPSHOT.jar"

# openvidu KMS
$ docker run -p 4443:4443 --rm -e OPENVIDU_SECRET=MY_SECRET openvidu/openvidu-server-kms:2.22.0
```

<br/><br/><br/>

## 🛠프로젝트 빌드 및 배포
- [프로젝트 빌드 및 배포](https://github.com/MoochangPark/GGANBU.GG/blob/master/exec/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8_%EB%B9%8C%EB%93%9C_%EB%B0%8F_%EB%B0%B0%ED%8F%AC.md)

<br/><br/><br/>

## ⚙시스템 환경 및 구성

![아키텍쳐_구성도](https://user-images.githubusercontent.com/119276371/204210085-733934c6-4cbd-4209-b18a-8f0a394384c8.png)


- OS: Windows10, Linux
- Backend Framework: Spring Boot 2.7.1
- Frontend Framework: Next 12.2.5
- DB: mongoDB version v6.0.1, mysql Ver 8.0.30-0ubuntu0.20.04.2 for Linux on x86_64 ((Ubuntu))
- WAS: Gradle
- JVM: javac 1.8.0_342
- Node.js: 
- React: 18.2.0
- npm: 8.5.5
- Docker: 20.10.12
- Jenkins: 
- WEB: Nginx (1.18.0)


<br/><br/><br/>

## 📕프로젝트 후기
- 최진욱: 가장 대중적인 리그 오브 레전드를 주제로 프로젝트를 진행해봐서 흥미가 있었습니다. open api를 활용해서 리그 오브 레전드의 데이터들이 어떻게 들어오는 지 알 수 있었고 생각보다 자세하게 데이터가 들어와서 놀랐습니다. hadoop을 사용하면서 공부하면서 hadoop이 쓰이는 방식에 대해서 알 수 있었습니다.

- 남현우: 파이썬을 이용한 데이터 수집부터 하둡에서의 데이터 처리를 거쳐 데이터를 db에 저장하고 이를 활용하는 api를 만들면서 기본적인 백엔드 공부에 많이 도움이 되었습니다. 중간 중간 데이터 처리과정의 자동화라던가 효율적인 업무 분배같은 부분에서 아쉬움도 많이 남았지만 게임 개발자를 꿈꾸는 입장에서 너무 소중한 경험을 했습니다. 너무 힘들기도 했지만 개발 내내 즐거운 시간이었습니다. 다들 굳!

- 강석민: Riot Open API를 사용해서 데이터를 수집하고 그 데이터를 마음대로 가공하여 서비스를 위해 사용한다는 사실 자체가 재미있었습니다. 더 나아가서 서비스를 사용하는 사용자들이 재미있다고 해주거나, 기능적, 디자인적으로 피드백을 해주는 것조차도 재미있고 뿌듯했습니다. 잊고 있었던 개발의 가치와 즐거움을 다시 한번 깨닫게 된 경험이었습니다. NoSQL을 경험해볼 수 있는 값진 시간이였습니다. 처음 사용해보는 MongoDB였지만 옆에서 도와주는 팀원 덕분에 즐겁게 프로젝트를 마무리할 수 있었습니다. 우리팀짱><

- 최영선: 특화 프로젝트에서 가장 좋아하는 게임인 리그오브레전드를 주제로한 프로젝트를 할 수 있어서 재밌었습니다. 공통때는 React를 특화때는 Next.js를 활용해 프로젝트를 해봤는데 프로젝트를 하면서 다양한 상황에 어떤 방식을 써야하고 오류가 생겼을때 어떤 원리로 생기는 오류인지 알 수 있어서 좋은 시간이였습니다. 
또 같은 팀원들과 2번째 프로젝트를 해서 너무 재밌었고 즐겁게 프로젝트 했습니다. 자율때는 헤어지지만 각자 재밌게 프로젝트 했으면 좋겠습니다. 감사합니다.

- 김지수: 첫 번째 프로젝트가 어떤 것을 해야할지 몰라 따라가기 급급했던 프로젝트라면 두번째 특화 프로젝트는 제가 원하는 것을 맡아서 해보고 좋아하는 것을 할 때 얼마나 재밌게 프로젝트를 즐기면서 효율적으로 할 수 있는지를 알 수 있는 좋은 경험이 되었던 프로젝트 였습니다. React의 프레임워크인 NextJs를 사용하면서 화면을 어떻게 구축하고 구성해 나갈 것인지에 대한 자신감을 많이 얻었던 프로젝트 였던 것 같습니다. 특히 지난번 프로젝트와 같은 팀원들과 한 팀으로 이번 프로젝트를 진행하다보니 그 시너지가 더 극대화가 된 것 같아 팀원들에게 감사하다는 말을 하고 싶습니다. 특히 같은 팀원들을 보면서 포기하지 않는 집념이라던지, 새로운 것을 알아갈 때의 즐거움 같은 것을 배울 수 있어 너무 좋은 시간이었습니다. 개인적으로 정말 기억에 남을 프로젝트일 것 같습니다.

- 박무창: 게임을 좋아하는 개발자로서 가장 좋아하는 게임의 API를 기반으로 주제를 정하고 프로젝트를 진행할 수 있어서 개발하면서 즐거웠습니다. 이전 프로젝트에서 경험하지 못했던 새로운 기술들을 익히고 접목시켜볼 수 있었고, 새로운 문제점들을 발견하고 수정해가는 과정을 통해 프론트엔드 개발에 대한 전반적인 지식을 기존보다 더욱 넓힐 수 있었습니다. 프로젝트를 진행하는 동안 저의 멈추지 않는 추진력을 버텨가면서 잘 따라와 준 팀원들에게 감사함을 표합니다.

<br/><br/><br/>

## 🎞최종산출물(시연 영상)
영상 링크?

<br/><br/><br/>


