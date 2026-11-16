<div align="center">

# RM Studio · 알엠스튜디오

**레거시를 클라우드로, 데이터를 안전하게, 아이디어를 제품으로.**
*Legacy to cloud, data moved safely, ideas into products.*

[![Email](https://img.shields.io/badge/Email-dvmoomoodv@gmail.com-4F46E5?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dvmoomoodv@gmail.com)
[![Georu](https://img.shields.io/badge/Open_Source-Georu-111111?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dvmoomoodv/georu-data-migration)

</div>

---

## 👋 About Us

**알엠스튜디오**는 엔터프라이즈 시스템의 **클라우드 이관 · 아키텍처**, 대규모 **데이터 마이그레이션**, **웹 서비스 구축**을 수행하는 IT 서비스 기업입니다.
ERP · 그룹웨어 · 커머스 · 공공/협회 시스템까지 여러 산업의 현장 경험을 바탕으로 분석부터 설계, 개발, 이행, 운영 안정화까지 책임집니다.
프로젝트에서 검증한 기술은 오픈소스와 자체 서비스로 만들어 공개합니다.

**RM Studio** is an IT services company specializing in **cloud migration & platform architecture**, large-scale **data migration**, and **web platform development**.
Drawing on experience across ERP, groupware, e-commerce, and public-sector systems, we take ownership from analysis and design through delivery and stabilization.

---

## 🛠 What We Do

| | 서비스 | Service |
|---|---|---|
| ☁️ | 레거시 IDC → 클라우드 이관 및 아키텍처 컨설팅 (AA/SA) | Cloud migration & architecture consulting |
| 🔄 | 미들웨어 · 런타임 현대화 (WebLogic/OHS → Tomcat/Nginx) | Middleware & runtime modernization |
| 🗄️ | 이기종 DB 데이터 이관 · 쿼리 튜닝 (Oracle · MSSQL → MySQL) | Database migration & query tuning |
| 🏢 | ERP · 그룹웨어 · 전자결재 시스템 구축/고도화 | ERP & groupware integration |
| 🌐 | 웹 서비스 기획 · 개발 · 퍼블리싱, 반응형 웹 · SEO | Web platforms, publishing & SEO |
| 📋 | 프로젝트 관리 · PMO · 기술 컨설팅 (Agile) | Project management & consulting |

---

## 📁 Projects

### ☁️ 삼성웰스토리 E-커머스 플랫폼 통합 프로젝트
**Samsung Welstory E-Commerce Platform Integration** · `2026.03 – 현재` · AA / SA · PL

삼성웰스토리 E-커머스 플랫폼의 Legacy IDC 서비스를 **Samsung Cloud Platform**으로 이관하고, WebLogic/OHS 기반 구조를 **Tomcat/Nginx**로 전환하고 있습니다.
- **아키텍처:** Legacy IDC 애플리케이션/시스템 구조 분석, 클라우드 이관 구조 검토
- **산출물:** 구조도, 상세분석서, 개발가이드
- **인프라:** 방화벽 정책 분석, 네트워크 변경 협의
- **개발 · 배포:** 변경된 런타임에 맞춘 소스 수정, Bamboo · Bitbucket 기반 배포 · 릴리즈 관리
- **PL:** 10명 규모 수행 조직의 업무 조율과 개발 지원

### 🗄️ 애경그룹 그룹웨어 고도화 프로젝트 2차
**AK Group Groupware Enhancement (Phase 2)** · `2025.07 – 2026.02` · 데이터 이관 전담

전자결재와 계열사 게시판 시스템의 **MSSQL → MySQL(Azure)** 대규모 데이터 이관을 전담해 일정 내에 완료했습니다.
- **분석:** SQL Server 2016 SP1 레거시 데이터 모델 분석, AS-IS 문서화
- **설계:** MySQL 8.0 TO-BE 스키마 설계, 도메인 · 테넌트 · 기간 단위 이관 전략 수립
- **재설계:** 기존 프로시저와 C# 프로그램을 분석해 이관 로직 재설계
- **개발 · 이행:** Spring Boot · Spring Batch 이관 프로그램 개발, 실행 계획 수립과 실제 이관 수행

### 📊 네이버 데이터랩 연동 쇼핑데이터 열람 서비스
**Naver Datalab Shopping Data Viewer** · `2025.01 – 2025.05` · 기획 · PM

네이버 데이터랩 API로 실시간 쇼핑 트렌드 데이터를 열람하는 웹 플랫폼을 구축했습니다.
- 서비스 기획, 데이터 수집 로직과 UI 흐름 설계 (Figma · Next.js)
- 개발 · 디자인 협업 체계 구성, 일정 관리와 산출물 검수

### 🏢 한국무역협회 프로젝트
**Korea International Trade Association (KITA)** · `진행 중`

---

## 🚢 Open Source

### [Georu](https://github.com/dvmoomoodv/georu-data-migration) — 거룻배처럼, 데이터를 나눠 안전하게 나르는 DB 이관 프레임워크

알엠스튜디오가 실제 이관 프로젝트(Oracle → MySQL, MSSQL → MySQL)에서 사용한 엔진을 고객사 코드와 분리해 공개한 **Spring Batch 기반 DB 이관 프레임워크**입니다.
변환 규칙(SQL · Java)만 작성하면 실행 · 안전장치 · 기록 · 보고는 프레임워크가 맡습니다.

- 실행 게이트, 실행 전 점검, 4단계 테스트 모드. TRUNCATE · DELETE는 실행하지 않음
- 청크 단위 진행률, 실행 이력, 보고서(JSON · CSV · XLSX · PDF)
- 운영 UI와 REST API

![Java 17](https://img.shields.io/badge/Java-17-orange?style=flat-square)
![Spring Boot 3.2](https://img.shields.io/badge/Spring%20Boot-3.2-6db33f?style=flat-square)
![License](https://img.shields.io/badge/license-Apache%202.0-blue?style=flat-square)

---

## 💻 Tech Stack

**Languages**<br>
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logoColor=white" />

**Backend**<br>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Batch-6DB33F?style=flat-square&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Framework-6DB33F?style=flat-square&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/MyBatis-000000?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" />
<img src="https://img.shields.io/badge/CodeIgniter-EF4223?style=flat-square&logo=codeigniter&logoColor=white" />
<img src="https://img.shields.io/badge/ASP.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/JSP-007396?style=flat-square&logo=openjdk&logoColor=white" />

**Frontend**<br>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxt&logoColor=white" />
<img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white" />
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white" />
<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white" />
<img src="https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black" />

**Database**<br>
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white" />
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" />

**Cloud & Infra**<br>
<img src="https://img.shields.io/badge/Samsung_Cloud_Platform-1428A0?style=flat-square&logo=samsung&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white" />
<img src="https://img.shields.io/badge/RHEL-EE0000?style=flat-square&logo=redhat&logoColor=white" />
<img src="https://img.shields.io/badge/CentOS-262577?style=flat-square&logo=centos&logoColor=white" />
<img src="https://img.shields.io/badge/IBM_AIX-052FAD?style=flat-square&logo=ibm&logoColor=white" />
<img src="https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black" />
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />

**DevOps & VCS**<br>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white" />
<img src="https://img.shields.io/badge/Bitbucket-0052CC?style=flat-square&logo=bitbucket&logoColor=white" />
<img src="https://img.shields.io/badge/Bamboo-0052CC?style=flat-square&logo=bamboo&logoColor=white" />
<img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" />
<img src="https://img.shields.io/badge/SVN-809CC9?style=flat-square&logo=subversion&logoColor=white" />

**Enterprise Solutions**<br>
<img src="https://img.shields.io/badge/WebSquare-0A5EB0?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/OZ_Report-E5322D?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/Oracle_ERP-F80000?style=flat-square&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/HCL_Notes-1E73BE?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/DHTMLX-2F80ED?style=flat-square&logoColor=white" />

**Design & Collaboration**<br>
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" />
<img src="https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square&logo=adobephotoshop&logoColor=white" />

**Expertise** — Database Migration · Query Tuning · Java Performance · Cloud Migration · Web Application Architecture · UI Component Development · Responsive Web · SEO · ITGC · Agile · Software Project Management & Consulting

---

## 📬 Contact

프로젝트 문의와 협업 제안은 언제든 환영합니다.
We're always open to new projects and collaborations.

✉️ [dvmoomoodv@gmail.com](mailto:dvmoomoodv@gmail.com)

<div align="center">
<sub>© RM Studio · 알엠스튜디오</sub>
</div>
