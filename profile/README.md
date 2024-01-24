# 🐣DoongG 
<p align="center">
  <img src="https://github.com/DoongG/.github/assets/101184549/61df701d-92d2-44dc-b39b-3e585a8125be" width="100%">
</p>

## 목차

1. [프로젝트 개요](#-프로젝트-개요)
   - [서비스 URL](#배포-링크)
   - [팀원](#-팀-멤버)
3. [시작하기](#-시작하기)
   - [백엔드 설정](#doongg-server-백엔드-설정)
   - [프론트엔드 설정](#doongg-client-프론트엔드-설정)
4. [기능 소개](#-기능-소개)
   - [로그인 및 마이페이지](#1️⃣-로그인--마이페이지-기능)
   - [핫딜 (쇼핑몰)](#2️⃣-핫딜-페이지)
   - [게시판](#3️⃣-게시판-페이지)
   - [자취방 리뷰](#4️⃣-자취방-리뷰-페이지)
5. [API 명세서](#-api-명세서)

</br>

## ✅ 프로젝트 개요


### **프로젝트 기획 의도**

> DoongG는 1인 가구를를 위한 통합 플랫폼입니다. 자취 경험이 있는 팀원 모두가 자취를 하며  **<u>"직접 겪은 불편함"</u>** 을 개선하고자 만든 프로젝트입니다.

### **프로젝트 기간**

> 23.11.08 ~ 23.12.08 (4주)

### **배포 링크**

> 🔖url : [https://doongg.site](https://doongg.site/)   


### **기술 스택**

**Front-End**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=black)
![React](https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![styled-components](https://img.shields.io/badge/Styled%20component-DB7093?style=for-the-badge&logo=styled-components&logoColor=black)
![Swiper](https://img.shields.io/badge/Swiper-6332F6?style=for-the-badge&logo=swiper&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-FFA500?style=for-the-badge&logo=zustand&logoColor=black)
![Quill](https://img.shields.io/badge/Quill-CC6699?style=for-the-badge&logo=quill&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=black)
![KakaoMap API](https://img.shields.io/badge/KakaoMap%20API-yellow?style=for-the-badge&logo=kakao&logoColor=black)


**Back-End**

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=black)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-8BC34A?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-4CAF50?style=for-the-badge&logo=spring-security&logoColor=white)
![Spring JPA](https://img.shields.io/badge/Spring%20JPA-388E3C?style=for-the-badge&logo=spring-data&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20Web%20Tokens&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=black)
![Docker](https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=black)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![AWS-EC2](https://img.shields.io/badge/amazone%20Ec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=black)
![AWS-S3](https://img.shields.io/badge/aws%20s3-569A31?style=for-the-badge&logo=amazons3&logoColor=black)
![AWS-Route53](https://img.shields.io/badge/amazon%20route53-8C4FFF?style=for-the-badge&logo=amazonroute53&logoColor=black)
![Certbot](https://img.shields.io/badge/Certbot-03A9F4?style=for-the-badge&logo=letsencrypt&logoColor=white)
 
<br/>

### **👪 팀 멤버**

<table>
  <thead>
    <tr>
      <th>담당업무</th>
      <th>이름</th>
      <th>세부역할</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2">Back-End</td>
      <td><a href="https://github.com/jaejae990921">심재운</a></td>
      <td><b>팀장</b> <br/>API 개발, DB 개발, <br/>Back-End개발(로그인&회원가입, 마이페이지, 핫딜, 미니게임, 자취방 리뷰), 보안 설정</td>
    </tr>
    <tr>
      <td><a href="https://github.com/eukkki210">류승기</a></td>
      <td><b>팀원</b> <br/>API 개발, DB 개발, <br/>Back-End개발(마이페이지, 게시판), 서버 간 통신&통합, 배포 서버 런칭&운영</td>
    </tr>
    <tr>
      <td rowspan="3">Front-End</td>
      <td><a href="https://github.com/keeemhs">김현승</a></td>
      <td><b>팀원</b> <br/>UI/UX설계, Front-End개발(로그인&회원가입, 마이페이지)</td>
    </tr>
    <tr>
      <td><a href="https://github.com/thbrthbr">이태희</a></td>
      <td><b>팀원</b> <br/>UI/UX설계, Front-End개발(게시판, 미니게임)</td>
    </tr>
    <tr>
      <td><a href="https://github.com/7jjin">조진형</a></td>
      <td><b>팀원</b> <br/>UI/UX설계, Front-End개발(핫딜, 자취방 리뷰)</td>
    </tr>
  </tbody>
</table>
 
<br/>

## **🌟 시작하기**

### **⚒️ 패키지 설치 및 빌드 방법**

#### **전제 조건**

- `Node.js가 설치되어 있어야 합니다 (버전 16.20.2).`
- `npm 패키지 관리자가 설치되어 있어야 합니다.`
- `Java가 설치되어 있어야 합니다 (버전 17.0.9).`
- `Gradle 빌드 도구가 설치되어 있어야 합니다.`

</br>

#### DoongG-Server (백엔드) 설정

 1. DoongG-Server 레포지토리를 복제합니다:
    
```
git clone https://github.com/DoongG/DoongG-Server.git
```

 2. 프로젝트 디렉토리로 이동합니다.
    
```
cd DoongG-Server
```
 3. Gradle을 사용하여 프로젝트를 빌드합니다:

```
gradle clean build
```
 4. 빌드가 완료되면 실행 가능한 JAR 파일이 build 디렉토리에 생성됩니다.
    
 5. 다음 명령을 사용하여 서버를 실행합니다:

```
java -jar build/libs/doongG-0.0.1-SNAPSHOT.jar
```
##### 서버는 기본적으로 http://localhost:8080에서 실행됩니다.

</br>

#### DoongG-Client (프론트엔드) 설정

 1. DoongG-Client 레포지토리를 복제합니다:
    
```
git clone https://github.com/DoongG/DoongG-Client.git
```

 2. 프로젝트 디렉토리로 이동합니다.
    
```
cd DoongG-Client
```
 3. 의존성을 설치합니다:

```
npm install
```
 4. 다음 명령으로 프로젝트를 시작합니다:

```
npm start
```
##### 서버는 기본적으로 http://localhost:3000에서 실행됩니다.

<br/>


## ✅ 기능 소개

### **1️⃣ 로그인 & 마이페이지 기능**

<p align="center">
  <img src="https://github.com/DoongG/.github/assets/101184549/6cbd51b3-f582-45ce-93a8-81b9e42a456b"
"width="100%">
</p>

- 복잡한 로그인 UI를 최소화하기 위해 로그인 로직을 최소화 했습니다.
- 마이페이지에서 비밀번호 변경 및 활동 정보를 확인 할 수 있습니다.
- 최신 버전의 Spring Security와 JWT를 활용하여 비인가 사용자의 비정상적인 접근을 막도록 구현했습니다.
- CoolSMS를 활용하여 전화번호 인증을 구현하여 회원 가입 시 본인 인증이 가능하도록 했습니다.


### **2️⃣ 핫딜 페이지**

<p align="center">
  <img src="https://github.com/DoongG/.github/assets/101184549/ca714367-3382-4720-b85c-8bb27e4ada62"
"width="100%">
</p>

- 핫딜 게시판은 기존 가격에 비해 비교적 저렴하게 올라온 상품들의 정보가 올라오는 게시판 입니다.
- 페이지 로딩 속도를 개선하기 위해 상품 상세페이지 및 결제 기능을 한 페이지에서 가능하도록 모달로 만들었습니다.


### **3️⃣ 게시판 페이지**

<p align="center">
  <img src="https://github.com/DoongG/.github/assets/101184549/d2872c17-b0e1-48ba-ba32-9b1df01f5ee1">
</p>

- 자취할 때 필요한 정보나 고민거리를 해결해주는 게시판 페이지입니다.
- React Quil을 활용하여 게시물 작성 기능을 구현했습니다.
- 기본적인 게시판 CRUD 기능 외에도 사용자 편의를 위해 검색 기능(통합,작성자,제목,해시태그 검색), 리액션 기능, 댓글&대댓글 기능을 구현했습니다.
- 우측에 미니 게임 요소를 넣어서 사용자에게 재밌는 요소를 넣었습니다.
- 미니 게임은 랜덤 메뉴 추천과 냉장고 요리사 기능을 제공하며, 냉장고 요리사는 식품의약품안전처 API를 이용해 갖고 있는 재료를 기반으로 요리할 수 있는 레시피를 추천하고 레시피 상세 정보를 노출하도록 구현했습니다.

### **4️⃣ 자취방 리뷰 페이지**

<p align="center">
  <img src="https://github.com/DoongG/.github/assets/101184549/394c076d-f8a2-463e-ae8e-18784c44935d">
</p>

- 자취방에 대한 리뷰를 공유할 수 있는 페이지입니다.
- 리뷰 작성과 선택한 리뷰의 정보를 볼 수 있습니다.
- 카카오맵 API를 활용하여 지도에 자취방의 위치에 마커를 찍어 리뷰를 남길 수 있도록 구현했습니다.

</br>


## 📘 API 명세서

> 이 프로젝트의 API 명세서는 Swagger를 통해 제공됩니다.
> </br>
> Swagger UI에서 자세한 API 정보를 확인하려면 백엔드 서버를 실행한 후 아래 링크를 클릭하세요.

[Swagger API 명세서 바로가기](http://localhost:8080/swagger-ui/index.html)

</br>

## ©️ 저작권

> 이 프로젝트는 MIT 라이선스에 따라 라이선스가 부여됩니다. - 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하십시오.



