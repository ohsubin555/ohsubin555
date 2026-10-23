<div align="center">

# 안녕하세요, 오수빈입니다 👋

**매일 한 줄씩 더 성장하는 백엔드 개발자**

</div>

<br>

## 🙋‍♀️ About Me

- 모델과를 학과 수석으로 졸업한 뒤, 개발로 진로를 정한 신입 백엔드 개발자입니다.
- 쌍용교육센터 **Java Full-Stack 개발자 양성 과정** (2026.05.11 ~ 2026.10.23 · 896시간)에서 Java, Spring, Oracle, AWS, Docker를 학습했습니다.
- 화면에 필요한 데이터가 어디서 만들어지고 어떤 과정을 거쳐 전달되는지 끝까지 확인하며 개발합니다.

<br>

## 🛠 Tech Stack

**Back-end**<br>
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-DC382D?style=flat-square&logoColor=white)
![JSP/Servlet](https://img.shields.io/badge/JSP%2FServlet-F8981D?style=flat-square&logoColor=white)

**Front-end**<br>
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

**Database**<br>
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**DevOps & Tools**<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

<br>

## 📂 Projects

### 🛒 [GoodPang](https://github.com/ohsubin555/GoodPang) — 쿠팡 벤치마킹 이커머스 웹 서비스

> 팀 프로젝트 (4인) · 2026.08 ~ 2026.09 (4주) · Java · JSP/Servlet · JDBC · Oracle<br>
> 프레임워크 없이 Front Controller와 Handler Mapping을 직접 구성한 Custom MVC 구조

**담당 기능**
- 주문 내역·상세 조회 / 주문 취소 내역 조회 / 배송 조회
- 주문 상태·조회 기간에 따른 조건별 검색
- 프로젝트 로고, 배너, 파비콘 등 공통 디자인 리소스

**해결한 문제**
- 1:N JOIN 후 ROWNUM 페이징 시 주문이 잘리는 문제 → 주문번호를 먼저 거르는 3중 서브쿼리 페이징으로 해결
- 여러 상품 주문 시 금액이 2~3배로 합산되는 문제 → 주문 총액과 상품별 금액의 계산 기준 분리
- 상품마다 배송비가 중복 부과되는 문제 → 주문 단위로 배송비 로직 일원화

### 🏦 [OnBank](https://github.com/ohsubin555/ONBANK) — 인터넷 뱅킹 웹 서비스

> 팀 프로젝트 · 2026.10.06 ~ 2026.10.23 (3주) · Spring Boot · Spring Data JPA · Spring Security · Thymeleaf · MySQL<br>
> 계좌 도메인(팀2) 담당

**담당 기능**
- 계좌 개설 · 계좌 상태 변경 · 계좌 / 상대계좌 즐겨찾기
- 입출금, 계좌이체 (10만 원 초과 타인 이체 시 OTP 인증)
- 예약이체 등록 · 조회 · 취소 및 스케줄러 자동 실행
- 자산관리 리포트 화면 (대출 연동)
- 메인 페이지, 로고 · 파비콘 디자인

<br>

## 📚 Study

쌍용교육센터 과정 중 작성한 수업 실습 저장소입니다.

| 저장소 | 내용 |
|---|---|
| [javaPro](https://github.com/ohsubin555/javaPro) | Java 기초 문법 실습 |
| [JavaClass](https://github.com/ohsubin555/JavaClass) | Java 개발환경(IDE) 설정 실습 · 수업 자료 정리 |
| [ORACLE-](https://github.com/ohsubin555/ORACLE-) | Oracle SQL · PL/SQL 일자별 실습 (HR · SCOTT 스키마) |
| [JDBCClass](https://github.com/ohsubin555/JDBCClass) | JDBC 실습, Controller · Service · DAO 구조의 게시판 구현 및 테스트 |
| [WebClass](https://github.com/ohsubin555/WebClass) | 웹 수업 전체 실습 (HTML · CSS · JavaScript · jQuery) |
| [JSPClass](https://github.com/ohsubin555/JSPClass) | JSP · Servlet 실습 (MVC 패턴 · 필터 · 세션), 회원 · 게시판 구현 |
| [SpringLegacyClass](https://github.com/ohsubin555/SpringLegacyClass) | Spring MVC · DI · AOP · MyBatis · 트랜잭션 · Spring Security 단계별 실습, 게시판(페이징 · 검색 · 댓글 · 파일 업로드) |
| [SpringBootClass](https://github.com/ohsubin555/SpringBootClass) | Spring Boot · JPA · Thymeleaf 실습 (방명록 · 게시판 · 영화 리뷰 · Security · JWT) |
| [ReactClass](https://github.com/ohsubin555/ReactClass) | React 컴포넌트 단계별 실습 |
| [react-practice](https://github.com/ohsubin555/react-practice) | React + Vite 게시판 CRUD 실습 |

<br>

## 📫 Contact

- Email: ohsubin555@naver.com
<!-- 노션 포트폴리오·기술 블로그가 생기면 아래 줄의 주석을 풀고 링크를 넣으세요 -->
<!-- - Portfolio: https:// -->
<!-- - Blog: https:// -->
