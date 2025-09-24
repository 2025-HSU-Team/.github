# 👂 소리 시각화 서비스 SoSAW

청각 제약 사용자를 위한 **실시간 소리 인식·시각화 서비스**  
일상 속 위험 신호부터 개인 맞춤형 알림까지, **직관적 인포그래픽과 진동 알림**을 제공합니다.  

---

## 📖 작품 개요 (Project Overview)

- 차량 경적, 화재 경보음 등 **위험 신호 실시간 감지**  
- 사용자에게 **인포그래픽 + 진동 알림** 전달  
- 세탁기 완료, 전자레인지 종료 등 **개인 맞춤형 생활 소리 등록 가능**  
- 등록된 소리도 동일한 방식으로 **시각화 + 알림 제공**  

---

## 📱 서비스 화면 (Service Screens)
### 🔹 일상생활 소리 탐지
주변의 소리를 실시간으로 탐지하고, 소리 종류에 따라 **인포그래픽과 원형 크기 변화**로 시각화합니다.  

![alt text](<Frame 2085667492.png>)

### 🔹 사용자 소리 추가
사용자가 원하는 소리를 직접 **녹음 및 등록**하고, 이후 동일하게 시각화 서비스를 제공합니다. 

![alt text](<Frame 2085667493.png>)
---

## 🛠 기술 스택 (Tech Stack)

### 🔹 Frontend
- **Flutter (Dart, Kotlin)** : 크로스플랫폼 앱 개발  
  

<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" />  
<img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" />  
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />  

---

### 🔹 Backend
- **Java 17 / Spring Boot 3.5.x** : 메인 서버  
- **PostgreSQL + pgvector** : 벡터 기반 유사도 검색  
- **Swagger (springdoc-openapi)** : API 문서화  

<img src="https://img.shields.io/badge/Java%2017-007396?style=flat-square&logo=java&logoColor=white" />  
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />  
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />  

---

### 🔹 AI / Signal Processing
- **FastAPI (Python)** : 오디오 특징 추출 서버  
- **Librosa / SoundFile / NumPy** : MFCC 추출  
- **TensorFlow Lite** : 소리 분류 모델  

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />  
<img src="https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />  
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />  

---

### 🔹 DevOps
- **Docker** : 컨테이너 기반 배포  
- **GitHub Actions** : CI/CD 자동화  
- **Vercel** : 초기 프론트 배포 
- **AWS EC2** : 운영 서버 환경  

<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />  
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />  
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />  
<img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazon-aws&logoColor=white" />  
