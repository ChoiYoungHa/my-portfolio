# ⛳My-Personal-Projects-Portfolio

*최종 업데이트: 2025년 01월 13일*

<br>

안녕하세요! 이 레포지토리는 **스스로 탐구하고 기획하여 진행한 다양한 미니 프로젝트들을 모아놓은 포트폴리오**입니다.😊 <br>

각 프로젝트는 문제 분석부터 아키텍처 설계, 구현, 그리고 테스트까지 전 과정을 포함하고 있습니다. 

<br>

### 🎖️ 인프라 프로젝트 목록 🎖️

| No | 프로젝트 이름 | 설명 | 주요 기술 | 참여<br> 인원 | 링크 | 날짜 |
|----|---------------|------|-----------|----------|------|------|
| 1  | **VMware vSphere HA Deep Dive** | VMware vSphere High availability 기능을 깊게 분석합니다.| vShpere, Cluster, Admission Control, Failover Response | &nbsp;&nbsp;👩‍👩‍👧‍👦<br>(4명)| [GitHub 링크](https://github.com/ChoiYoungHa/VMware_vSphere_HA_DeepDive) | 2024-09-13 |
| 2  | **Linux PAM 모듈로 보안정책 구성하기** | Linux Ubuntu 환경에서 유저생성 및 로그인 정책을 구성합니다. | Ubuntu, PAM, pwquality, Virtual Box| &nbsp;&nbsp;🙋(개인) | [GitHub 링크](https://github.com/ChoiYoungHa/Linux_PAM) | 2024-09-19 |
| 3  | **CPU 평균 부하(Load Average)에 대해 이해하기** | Linux 평균 부하와 CPU 사용률에 대한 차이를 이해하고 스트레스 테스트를 진행해봅니다. | Linux, CPU Stress, I/O Stress, mpstat| 👩‍👩<br> (2인) | [GitHub 링크](https://github.com/ChoiYoungHa/Linux_LoadAverage) | 2024-09-23 |
| 4  | **Docker Image Optimization** | Distroless, Muti-stage build, Docker Slim을 사용하여 도커 이미지 크기를 최적화합니다. | Docker Mutil-stage, Docker Slim, Docker ignore, Distroless | 👩‍👩<br>(2명) | [GitHub 링크](https://github.com/ChoiYoungHa/FISA3-DockerImageOptimization) | 2024-09-24 |
| 5  | **DevSecOps: 취약점 분석 및 슬랙 알람 자동화** | Git Action, Code Canning, Trivy를 이용하여 취약점 분석을 자동화하고 알람을 보내줍니다.  | Git Action, Code Scanning, Docker, Slack | 👩‍👩<br> (2명) | [GitHub 링크](https://github.com/ChoiYoungHa/FISA3-Docker-Trivyㄴ) | 2024-09-25 |
| 6  | **ElasticSearch Batch Indexing** | crontab 배치작업으로 3시간마다 뉴스기사를 수집하고, ElasticSearch에서 검색될 수 있게 합니다. | ELK Stack (Elasticsearch, Logstash, Kibana), Python, Crontab | &nbsp;&nbsp;👩‍👩‍👧‍👦<br>(4명) | [GitHub 링크](https://github.com/ChoiYoungHa/WooriFISA-ELK-Batch-Indexing) | 2024-09-20 |
| 7  | **DB서버 이중화 Active, Standby 구축 후 Migration 자동화** | VM1, VM2 각각의 서버에 데이터베이스 이중화 Active, Standby구축하고 2시간마다 DB 데이터를 마이그레이션 합니다. | Docker-Compose, Docker, Crontab, VirtualBox, ShellScript | &nbsp;&nbsp;🙋(개인) | [GitHub 링크](https://github.com/ChoiYoungHa/Active-Standby-DB-Migration) | 2024-09-27 |
| 8  | **Git Webhook Jenkins CI/CD Pipline 구축** | 애플리케이션을 개발단계부터 배포단계까지 자동화하여 빠르고 효율적으로 배포할 수 있게 CI/CD를 구축합니다. | Jenkins, Webhook, ShellScript, Docker | &nbsp;&nbsp;🙋(개인) | [GitHub 링크](https://github.com/ChoiYoungHa/FISA3-Jenkins-CICD) | 2024-10-01 |
| 9  | **MiniKube에 Spring App 배포** | 로컬환경에서 가볍게 쿠버네티스를 사용해보며 쿠버네티스의 컨셉과 구조를 이해합니다.  | MiniKube, Docker, Spring | &nbsp;&nbsp;🙋(개인) | [GitHub 링크](https://github.com/ChoiYoungHa/FISA3-MiniKube-Spring) | 2024-10-03 |
| 10  | **Kubernetes Cluster 부하 테스트🚀** | 로컬환경에서 Kubernetes 클러스터를 구축하고 피크타임에 서비스가 얼마나 버틸 수 있는지 시뮬레이션 해봅니다.  | Kubernetes, Jmeter, Nginx, Spring | &nbsp;&nbsp;👩‍👩(2명) | [GitHub 링크](https://github.com/ChoiYoungHa/FISA3-Kubernetes-Cluster-StressTest) | 2024-10-08 |
| 11  | **Jenkins AWS EC2, S3 CI/CD 구축** | Jenkins를 활용하여 AWS EC2, S3 환경에서 CI/CD 파이프라인을 구축합니다.  | Jenkins, EC2, S3, git webhook | 👩‍👩<br>(2명) | [GitHub 링크](https://github.com/ChoiYoungHa/Jenkins-EC2-S3-CICD) | 2024-10-11 |
| 12 | **Terraform을 활용한 AWS EC2, S3 구축** | Terraform을 사용하여 AWS S3 버킷과 EC2 인스턴스를 생성하고, 웹 호스팅을 위한 인프라를 코드로 관리합니다. IAM 역할/정책 설정 및 S3 정적 웹사이트 호스팅 구성을 포함합니다. | Terraform, AWS(S3, EC2, IAM), IaC | 👩‍👩<br>(2명) | [GitHub 링크](https://github.com/ChoiYoungHa/FISA3-Terraform-S3) | 2024-10-16 |
| 13 | **Terraform AWS VPC 구축** | Terraform을 사용하여 AWS 네트워크 인프라를 자동으로 구축합니다. VPC, 서브넷, 라우팅 테이블, 게이트웨이 등을 코드로 구성하여 안전하고 효율적인 네트워크 환경을 구현합니다. | Terraform, AWS(VPC, IAM), IaC | 👩‍👩<br>(2명) | [GitHub 링크](https://github.com/ChoiYoungHa/FISA3-Terraform-AWS) | 2024-10-17 |


<br>

### ✨ 백엔드 프로젝트 목록 ✨

| No | 프로젝트 이름 | 설명 | 주요 기술 | 참여 인원 | 링크 | 날짜 |
|----|---------------|------|-----------|----------|------|------|
| 1  | **Java 스트림 및 람다를 이용한 코드 리팩토링** | 기존 Java 코드를 Stream,Lambda, Optional을 사용해 현대적으로 리팩토링 | Java 17, Steam, Lambda, Optinal | &nbsp;&nbsp;👨‍👨‍👦‍👦<br>(4명)| [GitHub 링크](https://github.com/ChoiYoungHa/WooriFISA-java-stream-refactoring) | 2024-07-19 |
| 2  | **타이타닉 데이터 생존률 실시간 시각화** | RDB 테이블 변경사항을 Logstash가 실시간으로 감지하고, Kibana를 통해 생존률 지표를 시각화합니다. | ElasticSearch, Logstash, Kibana, Mysql | &nbsp;&nbsp;👩‍👩‍👧 <br>(3명) | [GitHub 링크](https://github.com/ChoiYoungHa/WooriFISA-ELK-RDB-Pipline) | 2024-07-25 |
| 3  | **JPA 신입사원 OJT** | 만약에 신입사원 JPA OJT를 진행한다면 어떤 JPA 문제를 내어 이해시킬 것인가 생각하며 만든 문제입니다. | Java, JPA, 영속성 컨텍스트, JPQL, N+1 문제 | &nbsp;&nbsp;👩‍👩‍👧‍👦 <br>(4명)| [GitHub 링크](https://github.com/ChoiYoungHa/WooriFISA-JPA-OJT) | 2024-08-02 |
| 4  | **Daily Travel** | 여행정보 비대칭을 해소하기 위해 만든 여행지 공유 SNS | Spring Boot, Spring Data JPA, RESTful API, Next.js | &nbsp;&nbsp;👩‍👩‍👧‍👦 <br>(4명) | [GitHub 링크](https://github.com/ChoiYoungHa/WooriFISA-DailyTravel) | 2024-08-16 |

---

이 포트폴리오는 지속적으로 업데이트됩니다.
