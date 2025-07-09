# Newjeans

## 0. 목차

1. [개요](#1-개요)
2. [Github주소 및 사용한 기술스택](#2-Github-및-사용한-기술스택)
3. [코딩 컨벤션](#3-코딩-컨벤션)
4. [역할 분담 및 개발 일정](#4-역할-분담-및-개발-일정)

## 1. 개요

-   **Newjeans**는 뉴스페이지를 구현해 낸 페이지 입니다.
-   뉴스CRUD, 댓글, 회원 기능이 있습니다.

## 2. 사용한 기술스택

### 2-1. GitHub 레포지토리 주소

-   **Back-End**

    > https://github.com/chaess01/Newjeans/tree/main/java

-   **Front-End**
    > https://github.com/chaess01/Newjeans/tree/main/pages

### 2-2. 사용한 기술스택

-   **Back-End**

    -   개발<br>
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=Selenium&logoColor=white"/>


-   **Front-End**

    -   개발<br>
       <img src="https://img.shields.io/badge/Bootstrapap-7952B3?style=flat-square&logo=bootstrap&logoColor=white"/> <img src="https://img.shields.io/badge/Heroku-430098?style=flat-square&logo=Heroku&logoColor=white"/> <img src="https://img.shields.io/badge/Atom-66595C?style=flat-square&logo=Atom&logoColor=white"/>

    **data-base, server **

    - 개발<br>
        <img src="https://img.shields.io/badge/angular.js-DD0031?style=flat-square&logo=angularjs&logoColor=white"/> <img src="https://img.shields.io/badge/Nuxt.js-00DC82?style=flat-square&logo=Nuxt.js&logoColor=white"/>



## 3. 코딩 컨벤션

### 3-1. 네이밍 컨벤션
-   **snake_case** : 패키지구조, 테이블명명
-   **PascalCase** : 클래스
-   **camelCase** : 파일명, 폴더명명


## 4. 역할 분담 및 개발 일정

### 4-1. 역할 분담

| 이의빈    | 권성아   | 장현주 | 채은열 |이신영  |
| --------- | -------- | --------- | --------- |
| 상세페이지 | 메인페이지 | 프론트ui | 회원 및 보안 |댓글 및 보안 |

-   상세페이지 (이의빈)

    -   게시글 수정 및 삭제
    -   사용자와 관리자의 구분된 화면 표시
    -   사이드 핫이슈 표시

-   메인페이지 (권성아)

    -   뉴스 메인 페이지 표시
    -   카테고리 표시
    -   날짜 표시
    -   검색 표시

-   프론트ui (장현주)

    -   인터페이스 구성
    -   사용자와의 상호작용
    -   사이드바 제작
    -   스핀박스 제작

-   회원 및 인증 (채은열)

    -   서비스 이용자의 계정 생성 및 관리
    -   JSON Web Token을 이용한 사용자 인증 구현
    -   사용자 및 관리자 구분 관리

-   댓글 및 보안 (이신영)
    -   댓글박스 UI 및 기능 구현
    -   댓글추천
    -   관리자의 댓글관리 가능
    -   로그인한 사용자 제한 처리

### 4-2. 개발 일정

-   GitHub Project, WBS로 일정 관리

<img src='./readme/wbs.png'>
