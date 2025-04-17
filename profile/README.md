# 프로젝트 개요

<table>
  <tr>
    <td>
      <img src="soonamu.png" alt="Navi" width="70px">
    </td>
    <td>
      <b style="font-size: 22px;">수나무</b><br/>
      <p style="font-size: 17px;">수학을 키우는 작은 씨앗 한 걸음씩 수학의 숲으로!</p>
    </td>
  </tr>
</table>

![main](main2.png)

<!-- ![main](main.png) -->

<br>

## 목차

1. [서비스 소개](#서비스-소개)
2. [서비스 목표](#서비스-목표)
3. [프로젝트 기간](#프로젝트-기간)
4. [팀원 소개](#팀원-소개)
5. [프로젝트 설계 및 구성](#프로젝트-설계-및-구성)  
   5-1. [서비스 아키텍처](#서비스-아키텍처)  
   5-2. [데이터베이스 설계](#데이터베이스)  
   5-3. [사용 기술](#사용-기술)
6. [주요 기능](#주요-기능)  

<br>

# 서비스 소개

 본 프로젝트는 수학 학습에 어려움을 겪는 아동, 일명 “난산증” 아동을 위한 맞춤형 수학교육 솔루션입니다.
 서울시 교육청은 이러한 아동을 조기에 발견하고 지원하기 위해 **‘BASA 프로그램’**을 도입하였습니다.
 저희 팀은 BASA 프로그램의 기획자이신 교수님과 협업하여, 난산증 증상 개선에 실효성 있는 솔루션을 제공하고자 합니다.

<br>

# 서비스 목표

- 공동 특허 출원을 통해 기술적 차별성과 우위를 확보

- 교육청 및 공공기관과의 연계 확장을 통한 플랫폼 제공

- 연구 기반의 정교한 분석 기법과 맞춤형 중재 솔루션을 온라인 플랫폼에 구현

- BASA 온라인 솔루션의 유효성 검증

- 기존 BASA 참여 교사의 사용성 피드백과 요구사항 반영을 통해 사용자 친화적 개선 지속

- 초등학교, 특수교육기관, 정부 기관과의 협업을 확대하여 사회적 가치 창출 실현

<br>

# 프로젝트 기간

### 2025.03.04 ~ 2025.04.11

<br>

#  팀원 소개

<table align="center">
  <tr>
    <td align="center" width="17%;">
      <img src="bunny12.png" alt=""/>
      <br/><sub><b>전성호</b><br/>
      <span>팀장</span><br/>
      <span>BE</span>
      </sub>
    </td>
    <td align="center" width="17%;">
      <img src="bunny1.png" alt=""/>
      <br/><sub><b>오지원</b><br>
      <span>BE</span>
      </sub>
    </td>
    <td align="center" width="17%;">
      <img src="bunny5.png" alt=""/>
      <br/><sub><b>김성조</b><br>
      <span>Infra/BE</span>
      </sub>
    </td>
    <td align="center" width="17%;">
      <img src="bunny9.png" alt=""/>
      <br/><sub><b>조건희</b><br>
      <span>FE</span>
      </sub>
    </td>
    <td align="center" width="17%;">
      <img src="bunny4.png" alt=""/>
      <br/><sub><b>이수호</b><br>
      <span>FE</span>
      </sub>
    </td>
    <td align="center" width="17%;">
      <img src="bunny8.png" alt=""/>
      <br/><sub><b>박해구</b><br>
        <span>FE</span>
      </sub>
    </td>
  </tr>
</table>

<br>

# 프로젝트 설계 및 구성

## 서비스 아키텍처

![architecture](architecture.png)

## 데이터베이스

![erd](image-2.png)

<br>

## 사용 기술

### 운영체제
---
- **로컬 개발 환경:** 
  
  ![windows11](https://img.shields.io/badge/Windows%2011-%230079d6.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)
- **서버 운영 환경:**

  ![amazonec2](https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
  ![linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)


### IDE & Editor
---
  ![IntelliJIDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
  ![vscode](https://img.shields.io/badge/vscode-0065A9?style=for-the-badge&logo=vscode&logoColor=white)
  ![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)


### 버전 & 이슈 관리 및 협업 도구
---
  ![git](https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white)
  ![gitlab](https://img.shields.io/badge/Gitlab-FC6D26?style=for-the-badge&logo=Gitlab&logoColor=white)
  ![notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
  ![jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white)


### 배포 환경 및 빌드 도구
---
  ![amazonec2](https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
  ![jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white)
  ![docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)
  ![nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
  ![gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white)

  - AWS EC2 (Ubuntu `22.04`)
  - Nginx `1.18.0`
  - Docker `28.0.1`
  - Jenkins (CI/CD) `2.501`
  - Gradle `8.11.1`

### BackEnd
---
  ![java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
  ![springboot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
  ![jpa](https://img.shields.io/badge/Spring_data_jpa-F37C20?style=for-the-badge&logo=SpringSecurity&logoColor=white)

  ![springcloudgateway](https://img.shields.io/badge/Spring%20Cloud%20Gateway-006600?style=for-the-badge&logo=spring&logoColor=white)
  ![eureka](https://img.shields.io/badge/Spring%20Cloud%20Eureka-B1361E?style=for-the-badge&logo=spring&logoColor=white)
  ![config](https://img.shields.io/badge/Spring%20Cloud%20Config-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

- JAVA (OpenJDK `17.0.14`)
- SpringBoot `3.4.1`
- Spring Cloud Gateway `4.1.0`
- Spring Cloud Eureka `4.0.3`
- Spring Cloud Config `4.1.0`

### FrontEnd
---
  ![flutter](https://img.shields.io/badge/flutter-02569B.svg?style=for-the-badge&logo=flutter&logoColor=white)
  ![dart](https://img.shields.io/badge/dart-0175C2.svg?style=for-the-badge&logo=dart&logoColor=white)

- Flutter `3.29.0`
- Dart `3.7.0`

### DB & Storage
---
![vault](https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=Vault&logoColor=black)
![mysql](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![mongodb](https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white)
![redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![minio](https://img.shields.io/badge/minio-C72E49.svg?style=for-the-badge&logo=minio&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

- Vault `1.19.0`
- MySQL `8.0.4`
- MongoDB `7.0.17`
- Redis `7.4.2`
- Minio `RELEASE.2025-03-12T18-04-18Z`
- RabbitMQ `4.1.0`

<br>

# 주요 기능
## 로그인/회원가입
<img src="login_screen.png" width="50%" height="100%"/>
<!-- ![login](login_screen.png) -->

## 아이 프로필 생성 및 선택
| 아이 정보 입력 | 프로필 선택 |
|---|---|
![addchild](add_child.png) | ![addchild](select_child.png)

## 학습 시작하기
수 인식, 혹은 사칙연산 카드를 클릭하여 학습할 내용 선택

<img src="main_list.png" width="50%" height="100%"/>

### 수 인식(EN) 학습 시작하기
- **레벨 별 과(1 ~ 4과) 선택 및 학습할 차시 선택**
  | 레벨 및 과 선택 | 차시 선택 |
  |---|---|
  ![en_lv1](en_lv1.png) | ![chapter](chapter.png)

- **수 인식(EN) 문제 유형**

  ![alt text](image-1.png)

  ![alt text](image.png)

### 사칙연산(M) 학습 시작하기
- **과(1 ~ 6과) 선택 및 학습할 유형 선택**
  | 과 선택 | 유형 선택 |
  |---|---|
  ![m_category](m_category.png) | ![m_chapter](m_chapter.png)

- **문제 풀이**

  ![m_problem1](m_problem1.png) | ![m_problem2](m_problem2.png)
  |---|---|

- **통계**
  | 날짜 별 문제 풀이 목록 | 문제 오답 유형 및 원인 확인 | 카테고리 전체 문제 풀이 통계 |
  |---|---|---|
  ![m_statistics1](m_statistics1.png) | ![m_statistics2](m_statistics2.png)| ![m_statistics3](m_statistics3.png)



