# FestSpot

### 공연을 찾고, 관람 경험을 나누는 국내 공연 커뮤니티

FestSpot은 공연예술통합전산망(KOPIS)의 공연 정보를 모아 보여주고, 공연 후기와 티켓 양도 정보를 나눌 수 있도록 만든 웹 서비스입니다. 공연 목록과 상세 정보, 일정 캘린더, 주제별 커뮤니티와 관리자 기능을 제공합니다.

> 코리아 IT 아카데미 4월 국비 팀 프로젝트

## 한눈에 보기

| 항목        | 내용                                                  |
| ----------- | ----------------------------------------------------- |
| 서비스      | 국내 공연·페스티벌 정보 및 커뮤니티                   |
| 주요 사용자 | 공연을 탐색하고 관람 경험과 티켓 정보를 나누려는 사람 |
| 핵심 기능   | 공연 목록·상세·캘린더, 커뮤니티, 회원·관리자 기능     |
| 기술 구성   | React, Spring Boot, MySQL                             |
| 배포 상태   | 프로젝트 종료 후 공개 배포 링크 없음                  |

## 문제와 해결 방식

공연 정보는 여러 서비스에 흩어져 있고, 관람 후기나 티켓 양도처럼 팬들끼리 나누고 싶은 정보도 각각 다른 공간에 올라옵니다. FestSpot은 KOPIS 공연 정보를 한곳에서 살펴보고, 공연 일정과 커뮤니티를 함께 이용할 수 있도록 구성했습니다.

## 사용자 흐름

1. 공연 목록에서 국내 공연, 페스티벌, 내한 공연을 살펴봅니다.
2. 공연 상세 화면에서 일정과 장소 등 정보를 확인하고 댓글을 남깁니다.
3. 캘린더에서 공연 일정을 확인하고, 커뮤니티에서 자유글·후기·양도 정보를 나눕니다.
4. 관리자는 KOPIS 공연을 검색해 서비스에 등록하거나 직접 공연 정보를 관리합니다.

## 주요 기능

| 기능      | 설명                                                                         |
| --------- | ---------------------------------------------------------------------------- |
| 공연 탐색 | 국내 공연·페스티벌·내한 공연을 구분해 목록과 상세 정보를 확인합니다.         |
| 공연 일정 | 공연 일정을 캘린더에서 확인합니다.                                           |
| 공연 댓글 | 공연 상세 화면에서 댓글을 작성하고 관리합니다.                               |
| 커뮤니티  | 자유·후기·양도 게시판에서 게시글, 이미지, 댓글과 대댓글을 관리합니다.        |
| 계정      | 회원가입, 로그인, Google·Kakao·Naver OAuth2 로그인, 마이페이지를 제공합니다. |
| 관리자    | KOPIS 공연 검색 및 등록, 자체 공연 정보 관리, 회원 관리를 지원합니다.        |

## 팀원 소개

| 이름          | 담당 업무                                                                                                                            |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| (팀장) 김호섭 | 프로젝트 설계, DB 구조 설계, 메인 화면 개발, 게시글 디자인 및 CRUD 구현, 댓글 및 대댓글 CRUD, KOPIS API 데이터 요청 query, 서버 배포 |
| 이수원        | 개발 과정 문서 정리 및 관리, 웹 페이지 디자인, 로그인, 회원가입 기능 구현, 게시글 상세 화면, 글쓰기 화면 디자인 및 구현, 댓글 CRUD   |
| 김광호        | DB 구조 설계, 관리자 페이지 기능 구현, 마이페이지, 전체 상단바, 상단바 모달창 구현                                                   |

## 화면

### 메인 화면

<img width="3200" height="1800" alt="FestSpot 메인 화면" src="https://github.com/user-attachments/assets/8299a8df-adcc-495a-8f57-03ff173c2557" />

### 메뉴 및 공연 탐색

<img width="3200" height="1800" alt="우측 메뉴바" src="https://github.com/user-attachments/assets/866276bf-8158-47b8-bf56-04e812b3d661" />

<img width="1649" height="927" alt="공연 목록 화면" src="https://github.com/user-attachments/assets/88d88c9c-80ab-4322-ba9f-b16063284a83" />

<img width="1649" height="927" alt="공연 상세 화면" src="https://github.com/user-attachments/assets/498b994d-0653-4ae6-a78c-6be808d37be0" />

### 회원 및 커뮤니티

<img width="3200" height="1800" alt="회원가입 화면" src="https://github.com/user-attachments/assets/be98dc6b-1cae-4438-bd11-9cd9b6e2a3fa" />

<img width="3200" height="1800" alt="개인정보 수정 화면" src="https://github.com/user-attachments/assets/6ac0147f-7f01-44f9-917d-fc8626b466fc" />

<img width="1650" height="927" alt="커뮤니티 화면" src="https://github.com/user-attachments/assets/1e31c1f2-2ab3-4420-8c14-8f26046d4afc" />

<img width="1650" height="927" alt="댓글 화면" src="https://github.com/user-attachments/assets/9f60d5aa-d812-441c-bbc7-aee5f853fa2a" />

<img width="3200" height="1800" alt="게시글 작성 화면" src="https://github.com/user-attachments/assets/f02a191a-ade0-4c15-a23a-f7cb0c1a4937" />

### 관리자

<img width="3200" height="1800" alt="관리자 페이지" src="https://github.com/user-attachments/assets/cd8d7dcf-7b9f-47bf-b82e-3460978416b7" />

<img width="1650" height="927" alt="관리자 공연 정보 수정 화면" src="https://github.com/user-attachments/assets/72feea26-6394-4338-5c1f-38e321e40b41" />

## 아키텍처

브라우저의 React 앱이 Spring Boot REST API와 통신하고, 백엔드는 MyBatis를 통해 MySQL에 접근합니다. KOPIS는 공연 정보 조회에, OAuth2 제공자는 소셜 로그인에 사용합니다. 업로드 이미지는 백엔드의 파일 저장 경로에서 관리합니다.

<img width="1425" height="853" alt="FestSpot 시스템 아키텍처" src="https://github.com/user-attachments/assets/11f8cc3c-bfde-405b-a9c3-25e2ec9514e7" />

## ERD

<img width="1518" height="725" alt="FestSpot ERD" src="https://github.com/user-attachments/assets/c0bce786-36b1-4f7e-a4ee-cb0ad9c51c09" />

## 기술 스택

| 구분        | 기술                                                 |
| ----------- | ---------------------------------------------------- |
| Frontend    | JavaScript, React 19, Vite, React Query, Zustand     |
| Backend     | Java 21, Spring Boot 3.4.8, Spring Security, MyBatis |
| Database    | MySQL                                                |
| 외부 연동   | KOPIS API, Google·Kakao·Naver OAuth2                 |
| 스타일링·UI | Emotion, MUI                                         |

## 프로젝트 구조

```text
.
├── festspot_front/            # React + Vite 웹 애플리케이션
│   └── src/
│       ├── page/               # 공연, 커뮤니티, 회원, 관리자 화면
│       ├── components/         # 공통 UI 및 기능 컴포넌트
│       ├── api/                # 백엔드 요청
│       └── querys/             # React Query 데이터 요청
└── festspot_back/FestSpot/     # Spring Boot API 서버
    └── src/main/
        ├── java/               # 컨트롤러, 서비스, 도메인
        └── resources/mapper/   # MyBatis SQL 매퍼
```

## 로컬 실행

### 준비 사항

- Java 21
- Node.js 및 npm
- MySQL 데이터베이스

### 백엔드 설정

저장소의 기본 Spring 프로필은 `local`입니다. 로컬 실행 전에 다음 항목을 `application-secret.yml` 또는 환경 변수로 제공해야 합니다.

- MySQL 접속 정보 (`spring.datasource.url`, `username`, `password`)
- JWT 서명 키 (`jwt.secret`)
- 사용할 소셜 로그인 제공자의 OAuth2 client ID와 secret

`application-secret.yml`은 저장소에서 제외되는 로컬 설정 파일입니다. 인증 정보나 비밀번호를 커밋하지 마세요. 또한 실행할 MySQL 서버와 프로젝트 스키마를 준비해야 합니다.

### 백엔드 실행

저장소 루트에서 실행합니다.

```bash
cd festspot_back/FestSpot
./mvnw spring-boot:run
```

Windows PowerShell에서는 다음과 같이 실행합니다.

```powershell
cd festspot_back/FestSpot
.\mvnw.cmd spring-boot:run
```

### 프론트엔드 실행

새 터미널에서 실행합니다. Vite 개발 서버는 기본적으로 `http://localhost:5173`에서 열리고, API는 `http://localhost:8080`의 백엔드에 연결됩니다.

```bash
cd festspot_front
npm install
npm run dev
```

## 프로젝트 자료

- [Notion 프로젝트 문서](https://www.notion.so/4-23f62a2d127080de8306ee22bb15ed51?source=copy_link)
- [팀 프로젝트 저장소](https://github.com/team-Louisoix/FestSpot)
