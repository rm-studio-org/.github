<div align="center">

# RM Studio · 알엠스튜디오

**레거시를 클라우드로, 데이터를 안전하게, 아이디어를 제품으로.**
*Legacy to cloud, data moved safely, ideas into products.*

[![Email](https://img.shields.io/badge/Email-dvmoomoodv@gmail.com-4F46E5?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dvmoomoodv@gmail.com)
[![Georu](https://img.shields.io/badge/Open_Source-Georu-111111?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dvmoomoodv/georu-data-migration)

</div>

---

## 👋 About Us

**알엠스튜디오**는 엔터프라이즈 시스템의 **클라우드 이관 · 아키텍처**, 대규모 **데이터 마이그레이션**, 그리고 **웹 서비스 구축**을 수행하는 개발 스튜디오입니다.
고객사 프로젝트를 수행하면서 얻은 경험을 오픈소스와 자체 서비스로 만들어 공개합니다.

**RM Studio** is a development studio specializing in **cloud migration & platform architecture**, large-scale **data migration**, and **web platform development**.
We turn what we learn on client projects into open source and our own products.

---

## 🛠 What We Do

| | 서비스 | Service |
|---|---|---|
| ☁️ | 레거시 IDC → 클라우드 이관, 아키텍처 설계 (AA/SA) | Cloud migration & application/system architecture |
| 🔄 | 미들웨어 전환 (WebLogic/OHS → Tomcat/Nginx) | Middleware modernization |
| 🗄️ | 이기종 DB 데이터 이관 (MSSQL · Oracle → MySQL) | Heterogeneous database migration |
| 🌐 | 데이터 연동 웹 플랫폼 기획 · 개발 (PM) | Data-driven web platforms |
| 🚢 | 오픈소스 DB 이관 프레임워크 Georu | Open-source migration framework |

---

## 📁 Projects

### ☁️ 삼성웰스토리 E-커머스 플랫폼 통합 프로젝트
**Samsung Welstory E-Commerce Platform Integration** · `2026.03 – 현재` · AA / SA · PL

Legacy IDC 서비스를 **Samsung Cloud Platform**으로 이관하고 WebLogic/OHS 기반 구조를 **Tomcat/Nginx**로 전환하는 프로젝트입니다.
- Legacy IDC 애플리케이션/시스템 구조 분석, 클라우드 이관 구조 검토
- 구조도 · 상세분석서 · 개발가이드 작성, 방화벽 정책 분석과 네트워크 변경 조율
- 변경된 런타임/인프라에 맞춘 소스 수정, Bamboo · Bitbucket 기반 배포 · 릴리즈 관리
- 10명 규모 팀의 PL로 문서 작성, 개발자 지원, 업무 조율

### 🗄️ 애경그룹 그룹웨어 고도화 프로젝트 2차
**AK Group Groupware Enhancement (Phase 2)** · `2025.07 – 2026.02` · Data Engineer (기여도 100%)

전자결재와 계열사 게시판 시스템의 **MSSQL → MySQL(Azure)** 대규모 데이터 이관을 혼자 맡아 일정 안에 끝냈습니다.
- SQL Server 2016 SP1 레거시 데이터 모델 분석과 AS-IS 문서화
- MySQL 8.0 TO-BE 스키마 설계, 도메인 · 테넌트 · 기간 단위 이관 전략 수립
- 기존 프로시저 · C# 프로그램을 분석해 이관 로직 재설계
- Spring Boot · Spring Batch 이관 프로그램 개발, 실행 계획 수립과 실제 이관 수행

### 📊 네이버 데이터랩 연동 쇼핑데이터 열람 서비스
**Naver Datalab Shopping Data Viewer** · `2025.01 – 2025.05` · PM

네이버 데이터랩 API로 실시간 쇼핑 트렌드 데이터를 열람하는 웹 플랫폼입니다.
- 서비스 기획, 데이터 수집 로직과 UI 흐름 설계
- 개발 · 디자인 협업 체계 구성, 일정 관리와 산출물 검수

### 🏢 한국무역협회 프로젝트
**Korea International Trade Association (KITA)** · `진행 중`

---

## 🚢 Open Source

### [Georu](https://github.com/dvmoomoodv/georu-data-migration) — 거룻배처럼, 데이터를 나눠 안전하게 나르는 DB 이관 프레임워크

실제 이관 프로젝트(Oracle → MySQL, MSSQL → MySQL)에서 쓰던 엔진을 고객사 코드와 분리해 공개한 **Spring Batch 기반 DB 이관 프레임워크**입니다.
사람은 변환 규칙(SQL · Java)만 작성하고, 실행 · 안전장치 · 기록 · 보고는 프레임워크가 맡습니다.

- 실행 게이트, 실행 전 점검, 4단계 테스트 모드. TRUNCATE · DELETE는 실행하지 않음
- 청크 단위 진행률, 실행 이력, 보고서(JSON · CSV · XLSX · PDF)
- 운영 UI와 REST API

![Java 17](https://img.shields.io/badge/Java-17-orange?style=flat-square)
![Spring Boot 3.2](https://img.shields.io/badge/Spring%20Boot-3.2-6db33f?style=flat-square)
![License](https://img.shields.io/badge/license-Apache%202.0-blue?style=flat-square)

---

## 💻 Tech Stack

**Backend**<br>
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Batch-6DB33F?style=flat-square&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/MyBatis-000000?style=flat-square&logoColor=white" />

**Database**<br>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" />
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" />

**Infra & Cloud**<br>
<img src="https://img.shields.io/badge/Samsung_Cloud_Platform-1428A0?style=flat-square&logo=samsung&logoColor=white" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black" />
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />

**DevOps & Collaboration**<br>
<img src="https://img.shields.io/badge/Bamboo-0052CC?style=flat-square&logo=bamboo&logoColor=white" />
<img src="https://img.shields.io/badge/Bitbucket-0052CC?style=flat-square&logo=bitbucket&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" />

**Frontend**<br>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />

---

## 📬 Contact

프로젝트 문의와 협업 제안은 언제든 환영합니다.
We're always open to new projects and collaborations.

✉️ [dvmoomoodv@gmail.com](mailto:dvmoomoodv@gmail.com)

<div align="center">
<sub>© RM Studio · 알엠스튜디오</sub>
</div>
