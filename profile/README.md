<img src="./assets/banner.png" alt="RM Studio" width="100%">

<div align="center">

<br>

**레거시를 클라우드로, 데이터를 안전하게, 아이디어를 제품으로.**<br>
<sub>LEGACY TO CLOUD · DATA MOVED SAFELY · IDEAS INTO PRODUCTS</sub>

<br>

[![Email](https://img.shields.io/badge/CONTACT-141412?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dvmoomoodv@gmail.com)
[![Georu](https://img.shields.io/badge/OPEN_SOURCE_·_GEORU-141412?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dvmoomoodv/georu-data-migration)

</div>

<br>

## 01 — About

**알엠스튜디오**는 엔터프라이즈 시스템의 **클라우드 이관 · 아키텍처**, 대규모 **데이터 마이그레이션**, **웹 서비스 구축**을 수행하는 IT 서비스 기업입니다.
ERP · 그룹웨어 · 커머스 · 공공/협회 시스템까지 여러 산업의 현장 경험을 바탕으로 분석부터 설계, 개발, 이행, 운영 안정화까지 책임집니다.
프로젝트에서 검증한 기술은 오픈소스와 자체 서비스로 만들어 공개합니다.

> **RM Studio** is an IT services company specializing in **cloud migration & platform architecture**, large-scale **data migration**, and **web platform development** — taking ownership from analysis and design through delivery and stabilization.

<br>

## 02 — What We Do

<table>
<tr>
<td width="50%" valign="top">

**Cloud & Architecture**<br>
<sub>레거시 IDC → 클라우드 이관, AA/SA 아키텍처 컨설팅</sub>

</td>
<td width="50%" valign="top">

**Middleware Modernization**<br>
<sub>WebLogic/OHS → Tomcat/Nginx 런타임 전환</sub>

</td>
</tr>
<tr>
<td valign="top">

**Data Migration**<br>
<sub>Oracle · MSSQL → MySQL 이기종 이관, 쿼리 튜닝</sub>

</td>
<td valign="top">

**ERP & Groupware**<br>
<sub>ERP · 그룹웨어 · 전자결재 구축 및 고도화</sub>

</td>
</tr>
<tr>
<td valign="top">

**Web Platform**<br>
<sub>웹 서비스 기획 · 개발 · 퍼블리싱, 반응형 웹 · SEO</sub>

</td>
<td valign="top">

**Project Management**<br>
<sub>PM · PL · 기술 컨설팅, Agile 수행</sub>

</td>
</tr>
</table>

<br>

## 03 — Projects

| Year | Project | Scope |
|:---:|---|---|
| `2026` | **삼성웰스토리 E-커머스 플랫폼 통합**<br><sub>Samsung Welstory E-Commerce Platform Integration</sub> | AA / SA · PL |
| `2026` | **한국무역협회 프로젝트**<br><sub>Korea International Trade Association</sub> | — |
| `2025 – 2026` | **애경그룹 그룹웨어 고도화 2차**<br><sub>AK Group Groupware Enhancement Phase 2</sub> | Data Migration |
| `2025` | **네이버 데이터랩 연동 쇼핑데이터 열람 서비스**<br><sub>Naver Datalab Shopping Data Viewer</sub> | Planning · PM |

<details>
<summary><b>삼성웰스토리 E-커머스 플랫폼 통합</b> — Legacy IDC → Samsung Cloud Platform</summary>

<br>

삼성웰스토리 E-커머스 플랫폼의 Legacy IDC 서비스를 **Samsung Cloud Platform**으로 이관하고, WebLogic/OHS 기반 구조를 **Tomcat/Nginx**로 전환하고 있습니다.

- **아키텍처:** Legacy IDC 애플리케이션/시스템 구조 분석, 클라우드 이관 구조 검토
- **산출물:** 구조도, 상세분석서, 개발가이드
- **인프라:** 방화벽 정책 분석, 네트워크 변경 협의
- **개발 · 배포:** 변경된 런타임에 맞춘 소스 수정, Bamboo · Bitbucket 기반 배포 · 릴리즈 관리
- **PL:** 10명 규모 수행 조직의 업무 조율과 개발 지원

</details>

<details>
<summary><b>애경그룹 그룹웨어 고도화 2차</b> — MSSQL → MySQL (Azure)</summary>

<br>

전자결재와 계열사 게시판 시스템의 **MSSQL → MySQL(Azure)** 대규모 데이터 이관을 전담해 일정 내에 완료했습니다.

- **분석:** SQL Server 2016 SP1 레거시 데이터 모델 분석, AS-IS 문서화
- **설계:** MySQL 8.0 TO-BE 스키마 설계, 도메인 · 테넌트 · 기간 단위 이관 전략 수립
- **재설계:** 기존 프로시저와 C# 프로그램을 분석해 이관 로직 재설계
- **개발 · 이행:** Spring Boot · Spring Batch 이관 프로그램 개발, 실행 계획 수립과 실제 이관 수행

</details>

<details>
<summary><b>네이버 데이터랩 연동 쇼핑데이터 열람 서비스</b> — Data-driven Web Platform</summary>

<br>

네이버 데이터랩 API로 실시간 쇼핑 트렌드 데이터를 열람하는 웹 플랫폼을 구축했습니다.

- 서비스 기획, 데이터 수집 로직과 UI 흐름 설계 (Figma · Next.js)
- 개발 · 디자인 협업 체계 구성, 일정 관리와 산출물 검수

</details>

<br>

## 04 — Open Source

<table>
<tr>
<td>

### [Georu](https://github.com/dvmoomoodv/georu-data-migration)
**거룻배처럼, 데이터를 나눠 안전하게 나르는 DB 이관 프레임워크**

알엠스튜디오가 실제 이관 프로젝트(Oracle → MySQL, MSSQL → MySQL)에서 사용한 엔진을 고객사 코드와 분리해 공개한 **Spring Batch 기반 DB 이관 프레임워크**입니다.
변환 규칙(SQL · Java)만 작성하면 실행 · 안전장치 · 기록 · 보고는 프레임워크가 맡습니다.

- 실행 게이트, 실행 전 점검, 4단계 테스트 모드. TRUNCATE · DELETE는 실행하지 않음
- 청크 단위 진행률, 실행 이력, 보고서(JSON · CSV · XLSX · PDF)
- 운영 UI와 REST API

<img src="https://img.shields.io/badge/Java_17-141412?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Boot_3.2-141412?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Apache_2.0-141412?style=flat-square" />

</td>
</tr>
</table>

<br>

## 05 — Tech Stack

| | |
|---|---|
| **Languages** | <img src="https://img.shields.io/badge/Java-141412?style=flat-square&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-141412?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/JavaScript-141412?style=flat-square&logo=javascript&logoColor=white" /> <img src="https://img.shields.io/badge/Python-141412?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/PHP-141412?style=flat-square&logo=php&logoColor=white" /> <img src="https://img.shields.io/badge/C%23-141412?style=flat-square&logo=dotnet&logoColor=white" /> <img src="https://img.shields.io/badge/SQL-141412?style=flat-square" /> |
| **Backend** | <img src="https://img.shields.io/badge/Spring_Boot-141412?style=flat-square&logo=springboot&logoColor=white" /> <img src="https://img.shields.io/badge/Spring_Batch-141412?style=flat-square&logo=spring&logoColor=white" /> <img src="https://img.shields.io/badge/Spring_Framework-141412?style=flat-square&logo=spring&logoColor=white" /> <img src="https://img.shields.io/badge/MyBatis-141412?style=flat-square" /> <img src="https://img.shields.io/badge/Node.js-141412?style=flat-square&logo=nodedotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Laravel-141412?style=flat-square&logo=laravel&logoColor=white" /> <img src="https://img.shields.io/badge/CodeIgniter-141412?style=flat-square&logo=codeigniter&logoColor=white" /> <img src="https://img.shields.io/badge/ASP.NET-141412?style=flat-square&logo=dotnet&logoColor=white" /> <img src="https://img.shields.io/badge/JSP-141412?style=flat-square&logo=openjdk&logoColor=white" /> |
| **Frontend** | <img src="https://img.shields.io/badge/React-141412?style=flat-square&logo=react&logoColor=white" /> <img src="https://img.shields.io/badge/Next.js-141412?style=flat-square&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Vue.js-141412?style=flat-square&logo=vuedotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Nuxt-141412?style=flat-square&logo=nuxt&logoColor=white" /> <img src="https://img.shields.io/badge/Angular-141412?style=flat-square&logo=angular&logoColor=white" /> <img src="https://img.shields.io/badge/HTML5-141412?style=flat-square&logo=html5&logoColor=white" /> <img src="https://img.shields.io/badge/Sass-141412?style=flat-square&logo=sass&logoColor=white" /> <img src="https://img.shields.io/badge/Bootstrap-141412?style=flat-square&logo=bootstrap&logoColor=white" /> <img src="https://img.shields.io/badge/jQuery-141412?style=flat-square&logo=jquery&logoColor=white" /> <img src="https://img.shields.io/badge/Webpack-141412?style=flat-square&logo=webpack&logoColor=white" /> |
| **Database** | <img src="https://img.shields.io/badge/Oracle-141412?style=flat-square&logo=oracle&logoColor=white" /> <img src="https://img.shields.io/badge/MySQL-141412?style=flat-square&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/MariaDB-141412?style=flat-square&logo=mariadb&logoColor=white" /> <img src="https://img.shields.io/badge/SQL_Server-141412?style=flat-square&logo=microsoftsqlserver&logoColor=white" /> |
| **Cloud & Infra** | <img src="https://img.shields.io/badge/Samsung_Cloud_Platform-141412?style=flat-square&logo=samsung&logoColor=white" /> <img src="https://img.shields.io/badge/AWS-141412?style=flat-square&logo=amazonwebservices&logoColor=white" /> <img src="https://img.shields.io/badge/Azure-141412?style=flat-square&logo=microsoftazure&logoColor=white" /> <img src="https://img.shields.io/badge/GCP-141412?style=flat-square&logo=googlecloud&logoColor=white" /> <img src="https://img.shields.io/badge/Kubernetes-141412?style=flat-square&logo=kubernetes&logoColor=white" /> <img src="https://img.shields.io/badge/VMware-141412?style=flat-square&logo=vmware&logoColor=white" /> <img src="https://img.shields.io/badge/RHEL-141412?style=flat-square&logo=redhat&logoColor=white" /> <img src="https://img.shields.io/badge/CentOS-141412?style=flat-square&logo=centos&logoColor=white" /> <img src="https://img.shields.io/badge/IBM_AIX-141412?style=flat-square&logo=ibm&logoColor=white" /> <img src="https://img.shields.io/badge/Tomcat-141412?style=flat-square&logo=apachetomcat&logoColor=white" /> <img src="https://img.shields.io/badge/Nginx-141412?style=flat-square&logo=nginx&logoColor=white" /> |
| **DevOps & VCS** | <img src="https://img.shields.io/badge/Git-141412?style=flat-square&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/GitLab-141412?style=flat-square&logo=gitlab&logoColor=white" /> <img src="https://img.shields.io/badge/Bitbucket-141412?style=flat-square&logo=bitbucket&logoColor=white" /> <img src="https://img.shields.io/badge/Bamboo-141412?style=flat-square&logo=bamboo&logoColor=white" /> <img src="https://img.shields.io/badge/Jenkins-141412?style=flat-square&logo=jenkins&logoColor=white" /> <img src="https://img.shields.io/badge/SVN-141412?style=flat-square&logo=subversion&logoColor=white" /> |
| **Enterprise** | <img src="https://img.shields.io/badge/WebSquare-141412?style=flat-square" /> <img src="https://img.shields.io/badge/OZ_Report-141412?style=flat-square" /> <img src="https://img.shields.io/badge/Oracle_ERP-141412?style=flat-square&logo=oracle&logoColor=white" /> <img src="https://img.shields.io/badge/HCL_Notes-141412?style=flat-square" /> <img src="https://img.shields.io/badge/DHTMLX-141412?style=flat-square" /> |
| **Design** | <img src="https://img.shields.io/badge/Figma-141412?style=flat-square&logo=figma&logoColor=white" /> <img src="https://img.shields.io/badge/Photoshop-141412?style=flat-square&logo=adobephotoshop&logoColor=white" /> |

<sub><b>EXPERTISE</b> — Database Migration · Query Tuning · Java Performance · Cloud Migration · Web Application Architecture · UI Component Development · Responsive Web · SEO · ITGC · Agile · Software Project Management & Consulting</sub>

<br>

## 06 — Contact

<table>
<tr>
<td width="140" align="center">
<img src="./assets/logo.png" alt="RM Studio logo" width="110">
</td>
<td>

프로젝트 문의와 협업 제안은 언제든 환영합니다.<br>
<sub>We're always open to new projects and collaborations.</sub>

✉️ [dvmoomoodv@gmail.com](mailto:dvmoomoodv@gmail.com)

</td>
</tr>
</table>

<div align="center">
<br>
<sub>© RM STUDIO · 알엠스튜디오</sub>
</div>
