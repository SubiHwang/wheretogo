
# 어디가농? 🌽

> **"데이터 기반 맞춤형 귀농 지역 추천 서비스"**  
우아한 자매들이 만드는 스마트한 귀농 가이드 🚜✨  

📽️ [시연 영상 바로가기](https://drive.google.com/file/d/1nhuQVSqwYE_Bl4Ter0TAZ4RBhGhQi_vt/view) 
📝 [회의록 보기](https://cloud-ice-455.notion.site/1d515a2ee9308155bc00c09a12c43fbe?pvs=4)


## 목차

🌱 어디가농? 서비스 소개
<br>
⏰ 개발 기간
<br>
💡 기획 배경
<br>
🎯 목표 및 주요 기능
<br>
🔧 기능 소개
<br>
📢 기술 스택 소개
<br>
🔍 시스템 아키텍처
<br>
💾 ERD 다이어그램
<br>


## 👥 팀 소개 및 역할

### ⏰ 개발 기간 (6주)
2025.03.03 ~ 2025.03.14 (2주) 기획, 설계
<br>
2025.04.15 ~ 2025.04.11 (4주) 개발

### 💡 기획 배경

귀농을 고려하는 사람들은 지역 선택에 많은 어려움을 느낍니다. <br>환경, 비용, 인프라 등 다양한 요소를 고려해야 하지만, 이러한 정보를 종합적으로 제공하는 서비스가 부족합니다.<br>
또한 귀농 후 실패율이 높은 이유 중 하나는 충분한 정보와 준비 없이 결정하는 경우가 많기 때문입니다. <br>귀농 희망자가 더 현명한 선택을 할 수 있도록 데이터에 기반한 맞춤형 추천과 경험자와의 소통 기능을 결합한 서비스를 기획했습니다.


### 🎯 목표 및 주요 기능

**데이터 기반 의사결정 지원**

공공 빅데이터와 데이터 분석을 통한 객관적인 지역 정보 제공
사용자 우선순위를 반영한 맞춤형 추천 알고리즘 적용


**귀농 커뮤니티 활성화**
실제 귀농인과 예비 귀농인을 연결하는 멘토-멘티 시스템 구축



### 🔧 기능 소개

서비스의 주요 기능들을 소개합니다.

#### ✅ 메인

![image](https://github.com/user-attachments/assets/8e72755c-4509-4791-a2aa-e0b1ee21f19d)
![image](https://github.com/user-attachments/assets/50f32867-bf65-4e68-b4cf-e40c0cc9dc51)
![image](https://github.com/user-attachments/assets/8e18ad69-19e1-4bc6-9ddf-a5318e3f814d)


#### ✅ 로그인

이메일과 비밀번호로 로그인
![image](https://github.com/user-attachments/assets/53359963-45dc-48f4-ac46-e758ef96a8aa)

#### ✅ 설문조사


맞춤형 리포트를 제공받기 위한 설문조사 
![image](https://github.com/user-attachments/assets/55e2aadb-d13e-4731-b441-ce632e246ed9)
![image](https://github.com/user-attachments/assets/9775d9d5-f59b-46e6-8b8e-ceaa3fd2cfba)


#### ✅ 지역 추천 리포트 

사용자가 한 설문조사를 기반으로 우선순위(환경, 교통, 인프라, 생활)에 따른 개인화된 지역 추천
![image](https://github.com/user-attachments/assets/5d2e52a1-5645-4b33-8174-a8d85bf5eb47)
![image](https://github.com/user-attachments/assets/a3905b73-38d0-40a0-a86b-a076d0e5520b)


#### ✅ 마이페이지 

제공된 귀농 리포트, 예상 수익 리포트 조회 
회원 정보 수정 및 정보 조회 

![image](https://github.com/user-attachments/assets/064f869c-b284-440c-b65b-25187fea0140)
![image](https://github.com/user-attachments/assets/e4d9cb59-548c-4468-88e6-0879cca222bf)


#### ✅ 멘토 & 멘티 

지도에서 지역 선택 후 멘토 조회
![image](https://github.com/user-attachments/assets/73515a2c-71db-4c03-b114-05be93140e18)
![image](https://github.com/user-attachments/assets/e917a865-b4e1-466b-b4d2-6a2394511f82)



#### ✅ 실시간 채팅

실시간 채팅과 실시간 알림 조회 
![image](https://github.com/user-attachments/assets/d0086afe-a367-4b1b-9d00-cf697bfe7561)
![image](https://github.com/user-attachments/assets/e8a6abac-c99b-49b7-aa34-f856b490c92f)


#### ✅ 멘토 등록

회원가입한 멘티는 멘토로 등록 가능 
![image](https://github.com/user-attachments/assets/5542f865-12ba-4a25-b56c-fc623ad44d0f)

#### ✅ 뉴스

Naver API로 실시간 뉴스 조회 
![image](https://github.com/user-attachments/assets/c21290cb-0ffe-4517-ab01-fe93792ca824)



#### ✅ 지원 정책 

웹 크롤링으로 데이터 수집 후 지역별 지원 정책 조회

![image](https://github.com/user-attachments/assets/7cd147a6-0944-412f-ab26-a46ae21d6a89)
![image](https://github.com/user-attachments/assets/f9ce652a-3aa6-459a-b8b2-b77aea0c55f4)


## 📢 기술 스택 소개

#### Big-data distribution
![Hadoop](https://img.shields.io/badge/Hadoop-3.3.6-66CCFF?logo=apachehadoop)
![Spark](https://img.shields.io/badge/Apache%20Spark-3.5.0-E25A1C?logo=apachespark)
![Zeppelin](https://img.shields.io/badge/Zeppelin-0.10.1-2D2D2D?logo=apachezeppelin)
![Zookeeper](https://img.shields.io/badge/Zookeeper-3.7.1-7E3794?logo=apachezookeeper)

#### Frontend
![React](https://img.shields.io/badge/React-18.3.1-61DAFB?logo=react)
![Vite](https://img.shields.io/badge/Vite-6.0.5-646CFF?logo=vite)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=000)
![Redux](https://img.shields.io/badge/Redux-Toolkit-764ABC?logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.3.3-38B2AC?logo=tailwindcss)

#### Backend 
![Java](https://img.shields.io/badge/Java-17-blue?logo=java)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.4.3-brightgreen?logo=springboot)
![JPA](https://img.shields.io/badge/JPA-Hibernate-59666C?logo=hibernate)
![JWT](https://img.shields.io/badge/JWT-Authentication-000000?logo=jsonwebtokens)
![Gradle](https://img.shields.io/badge/Gradle-7.6-02303A?logo=gradle)

#### Data Processing & ML
![Pandas](https://img.shields.io/badge/Pandas-1.5.3-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-1.24-013243?logo=numpy)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.4.1-F7931E?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.1-11557C?logo=matplotlib)
![Jupyter](https://img.shields.io/badge/Jupyter-Lab-orange?logo=jupyter)

#### Build & Deployment
![EC2](https://img.shields.io/badge/AWS%20EC2-t3.medium-FF9900?logo=amazonaws&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker--Compose-2496ED?logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-Automation-D24939?logo=jenkins)
![Nginx](https://img.shields.io/badge/Nginx-1.27.4-009639?logo=nginx)

#### Database & Cache
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14-336791?logo=postgresql)
![Redis](https://img.shields.io/badge/Redis-7.2-DC382D?logo=redis)

#### Infrastructure
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-E95420?logo=ubuntu)
![Prometheus](https://img.shields.io/badge/Prometheus-Metrics-orange?logo=prometheus)
![Grafana](https://img.shields.io/badge/Grafana-Dashboard-F46800?logo=grafana)


## 🔍 시스템 아키텍처
![image](https://github.com/user-attachments/assets/a1861979-ff60-435d-94f5-f99d4eef3173)



## 💾 ERD Diagram

![image](https://github.com/user-attachments/assets/25e6582d-6a8f-4ae5-b718-7d149bea07ef)


## 👥 우아한 자매들

우아한 자매들은 프론트엔드 3명, 백엔드 3명으로 구성된 팀입니다.

![image](https://github.com/user-attachments/assets/090550b4-980e-42d7-ba17-ff654f921130)


| Frontend | Frontend | Frontend | Backend | Backend | Backend |
|--------------|--------------|--------------|--------------|----------|--------------|
| 순화 👑 | 가영 | 미연 | 수비 | 시윤 | 나금 |

