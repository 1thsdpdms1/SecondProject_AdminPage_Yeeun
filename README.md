# ✈AdminPage_GroupAirTeamProject✈

<div style="text-align: center;">

  ![logo](https://github.com/1thsdpdms1/SecondProject_AdminPage_Yeeun/assets/154856610/26c1d58c-949b-4250-887a-1e22df8a065d)

<br>
GroupAir 항공사 관리자 페이지로 <br>
이해하기 쉬운 UI와 부서 간의 의사소통이 원할하도록한 커뮤니티<br>
또한 권한에 따라 관여할수있는 부분 제한하였습니다

사원, 부장, 대표이사 권한으로 나뉘어져있으며 <br>
부서관리, 결제관리, 일정관리, 근태관리, 급여관리, 사원관리 등등 관리프로그램

영화API, 날씨 API, 버스API를 사용하여 사용자의 편의성도 높여보았습니다
</div>

## 📌 목차

* [🔎프로젝트 소개](#프로젝트-소개)
  + [✔ 프로젝트 기본설정 ✔](#프로젝트-기본설정)
  + [✔ 기술스택 ✔](#프로젝트-기본설정)
  + [✔ 팀원소개 ✔](#Chatbot-구현)
  + [✔ 팀원소개 ✔](#팀원소개)
  + [✔ DB설계 ✔](#DB설계)
* [⭐프로젝트 시안](#프로젝트-시안)
  + [✔ 1. 로그인 페이지 구현 ✔](#-1-로그인-페이지-구현-)
  + [✔ 2. 회원등록 페이지 구현  ✔](#-2-회원등록-페이지-구현-)
  + [✔ 3. 회원관리 페이지 구현 ✔](#-3-회원관리-페이지-구현-)
  + [✔ NAVER API 연동 구현 ✔](#-4-naver-api-연동-구현-)


## ⚙프로젝트 소개

<details>
<summary>프로젝트 기본설정</summary>

|제목|내용|
|------|---|
|일정|2024/05/11~2024/06/07|
|인원|팀장 1명, 팀원 4명 (총 5인) _팀장으로 참여|
|주제|항공 관리자 페이지|



  
<li> 2024/05/11~2024/06/07 </li>
<li> 항공 관리자 페이지 </li>
<li> 팀장 1명, 팀원 4명 (총 5인) _팀장으로 참여 </li>
<li> 프로젝트명 : GroupAir TeamProject </li>
<li> 프로그래밍 언어 : JAVA </li>
<li> 프레임워크 : Springboot 2.7.11 </li>
<li> 데이터베이스 : MySql8 </li>
<li> 개발툴 : IntelliJ </li>
<li> 템플릿 엔진 : Thymeleaf (HTML + css) </li>
</details>

<details>
<summary> 기술스택 </summary>
<img src="https://img.shields.io/badge/javaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white">
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot**&logoColor=white">
<img src="https://img.shields.io/badge/springsecurity-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white">
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/amazonwebservices-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white">
<img src="https://img.shields.io/badge/amazonrds-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white">
<img src="https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">
<img src="https://img.shields.io/badge/amazonecs-FF9900?style=for-the-badge&logo=amazonecs&logoColor=white">
<img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">



</details>

<details>
<summary> 팀원소개</summary>

<table>
  <tbody>
    <tr>
      <th align="center"><a href=""><img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/e4f3a019-1688-4879-bf23-9e791e3b56a5" width="100px;" alt=""/><br /><sub><b>FE 팀장 : 손예은</b></sub></a><br /></th>
      <th align="center"><a href=""><img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/a92bfe84-63f4-45b1-800c-4fc5c8512513" width="100px;" alt=""/><br /><sub><b>FE 팀원 : 박**</b></sub></a><br /></th>
      <th align="center"><a href=""><img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/ea52beb1-8420-4f6b-9028-ff0f247dc895" width="100px;" alt=""/><br /><sub><b>FE 팀원 : 이** </b></sub></a><br /></th>
      <th align="center"><a href=""><img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/becb61fa-7a36-43fc-a00c-aa20be5ec767" width="100px;" alt=""/><br /><sub><b>FE 팀원 : 심 **</b></sub></a><br /></th>
      <th align="center"><a href=""><img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/c690bc9c-0d05-4067-a3d6-5ece66b61620" width="100px;" alt=""/><br /><sub><b>FE 팀원 : 조** </b></sub></a><br /></th>
</tr>
<tr>

<td>CI/CD, DB설계, <br>로그인, <br>naver(oauth, Mail, 조직연동),<br> 사원관리</td>
<td> 회사일정, 게시판 관리 </td>
<td> db설계, 근태관리, <br>급여관리, 항공편관리(map) </td>
<td> chatbot, 부서관리 </td>
<td> 결재관리</td>
</tr>
  </tbody>
</table>


</details>


<details>
<summary> 타임라인</summary>

![image](https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/c491040a-4bc0-43e9-9675-2a06484d6661)

</details>

<details>
<summary> DB설계 </summary>

![image](https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/ea0ccc32-1659-4d5e-845d-26a46bcbff69)


</details>
<br>


<br>
## ⭐프로젝트 시안

![0index](https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/db119b68-1233-4c54-aada-19e26998e761)


### ✔ 1. 로그인 페이지 구현 ✔
<details>
<summary>로그인 페이지 구현 시연 영상</summary>

![로그인](https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/3dd99fdb-f2d5-4347-b780-07eb49913627)


</details>

<details>
<summary>로그인 페이지 구현 시안 </summary>

<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/be6cd692-0bf4-4d4f-a77c-b4a98c5c544b" width="700" height="400"/>

- admin이 등록한 사원만 로그인이 가능하며 컨셉에 맞는 로고와 색상을 사용해 디자인
- 로그인 실패 시에는 예외처리를 위한 스프링 시큐리티의 커스텀 인증실패 핸들러를 사용
- 발생한 예외에 따라 적절한 메세지를 설정
- 로그인 실패시 로그인창 하단에 예외문구를 띄워 처리

<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/5c1c70f6-6ba7-437d-9e1d-406e29c03b2f" width="700" height="400"/>

- 로그인시 자신의 정보가 잘 기억이 나지 않는다면 아이디 찾기와 비밀번호 찾기 가능
- 아이디 찾기는 자신의 이름과 전화번호를 입력하게 하고 그 정보를 가지고 findUserEmailByNameAndPhone을 사용하여 이메일(즉 아이디)를 찾아
alert창에 나오도록 함

<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/31f6aeb1-ab88-4cbd-9a7a-e1cccb5f8fe5" width="700" height="400"/>

- 비밀번호 찾기는 이메일과 이름을 입력하게 하여 그 정보를 가지고 findUserPwByUserEmailAndName을 사용하여 그 회원을 찾고 새비밀번호로 변경하도록
- 이 과정이 끝나고 로그인시도를 할수있도록 로그인페이지로 이동하게 설정

</details>
<br>
<br>

### ✔ 2. 회원등록 페이지 구현 ✔
<details>
<summary>회원등록 구현 시연 영상</summary>

![회원등록](https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/d0fb066b-f951-44fc-ae44-57fa2ac0b4f7)

</details>

<details>
<summary>회원등록 구현 시안 </summary>

<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/0ab7a1f7-413d-4223-9bba-540187f8b6a3" width="700" height="400"/>

- admin권한으로 로그인시 회원 등록메뉴가 추가로 보여지며 회원을 등록시킬수있습니다
- 페이지의 기능들을 소개하자면 이메일 유효성 검사 및 초기 비밀번호 설정,부서연동 ,카카오 주소 api사용, 전화번호 자동 하이픈 기능이 있습니다

<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/a8d28892-f1bd-4ec6-b885-14106e56702d" width="700" height="400"/>

- 이메일을 입력하고 버튼을 누르면초기 비밀번호로 사용될 6자리의숫자를 랜덤함수를 이용해 만들고 입력받은 메일주소를 매개변수로한 매서드가 실행
- MimeMessageHelper는 이메일의 속성을 설정할수있는데 이때 수신자를 입력받은 메일주소로 설정, 내용에는 초기 비밀번호에 사용할 랜덤한 숫자를 포함한 메세지를 작성
- 그외 발신자와 이메일의 제목을 설정
- 발신이 완료되면 alert창과 함께 비밀번호 input창에 초기 비밀번호 값이 입력
  <img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/952718cf-2e9c-468d-844c-c748e7652d92" width="700" height="400"/>

- 주소입력시 카카오api를 사용하여 통일된 주소값을 가지도록 구현
- 우편번호찾기버튼을 클릭시 카카오 주소검색창이 뜨고 우편번호와 주소값이 input창에 입력
- 상세주소는 직접 입력할수있으며 위 주소와 상세주소를 합친 주소를 만들어 합친주소를 db에 저장

</details>
<br>
<br>

### ✔ 3. 회원관리 페이지 구현 ✔
<details>
<summary>회원등록 구현 시연 영상</summary>

![회원디테일](https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/6e3c2d0d-9cd8-496f-9383-d3ee2a981f7c)

</details>

<details>
<summary>회원등록 구현 시안 </summary>
<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/65a17770-addd-41a4-9d60-75ac817e5bf6" width="700" height="400"/>
<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/3010afbe-2b53-43e1-9d3a-d8c3ebdf8f12" width="700" height="400"/>
<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/b883b030-df45-4a52-bd27-68d95083c450" width="700" height="400"/>
</details>

<br>
<br>

### ✔ 4. NAVER API 연동 구현 ✔
<details>
<summary> NAVER API 연동 시연 영상</summary>

![네이버](https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/96a948d0-07f1-4625-8088-f524f15b0065)

</details>

<details>
<summary> NAVER API 연동 시안 </summary>
<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/be052358-a031-490a-8b61-10930ba24942" width="700" height="400"/>
<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/2e1e1442-558d-4335-b5c9-a3922b37945c" width="700" height="400"/>
<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/548c880f-211b-4698-bda5-41e0c9904ed5" width="700" height="400"/>
<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/849ec12c-b34c-4f6d-8206-40a5813fdcc2" width="700" height="400"/>
<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/cdb9263e-9560-4150-9576-8fabba21b7bb" width="700" height="400"/>
<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/37645692-79d7-4979-83bf-99dc63a215fe" width="700" height="400"/>
<img src="https://github.com/1thsdpdms1/FirstProject_ShopingMall_Yeeun/assets/154856610/98eb68f9-994b-4c00-8cc0-13f391ffe24e" width="700" height="400"/>
</details>
