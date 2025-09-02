###### Other Language
[English](https://github.com/dkssud-dus/cloneCoding-Class101/blob/main/README_en.md) | [한국어](https://github.com/dkssud-dus/cloneCoding-Class101/blob/main/README.md) | [日本語](https://github.com/dkssud-dus/cloneCoding-Class101/blob/main/README_ja.md)

<br/><br/><br/>

# Class 101
![1](https://github.com/user-attachments/assets/b76aeb8c-86bd-48db-ba7a-70cf77b09145)

<br/><br/>

**Class 101의 웹사이트를 클론 코딩하며 레이아웃과 동적 기능 구현을 연습한 개인 프로젝트**
> 해당 프로젝트는 실제 서비스인 Class 101 웹사이트를 참고하여 제작한 클론 코딩입니다. 메인 페이지와 네 개의 서브페이지를 중심으로 화면 구성을 재현하였고, 반복되는 레이아웃 요소를 컴포넌트화하여 관리하는 방법을 연습했습니다. DOM 조작과 setInterval을 활용한 타이머, 아코디언 메뉴, 장바구니 기능 등을 구현하여 인터랙션 요소를 실습하였습니다.

<br/><br/><br/>

## Link
- 바로가기 (Web-site): https://dkssud-dus.github.io/cloneCoding-Class101/index.html

<br/>

## Table of Contents
- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Environment & Contribution](#environment--contribution)
- [Contact](#contact)

<br/>

## Overview
### Background
클래스 101은 다양한 분야의 지식이나 스킬을 유료로 구매하거나 구독하여 강의를 학습할 수 있는 플랫폼이다.

<br/>

### Purpose
- `HTML` 구조화에 대해 연습한다.
- 레이아웃 설계에 대해 연습한다.
- `fetch` 등 `JS`의 주요 기능을 학습하고, 다음 프로젝트에 연계될 수 있도록 한다.
  
<br/>

### Keywords
`레이아웃 설계`
- `Flex` 를 활용한 구조적 페이지 배치     
  
`컴포넌트 재사용`
- Header/Footer를 `fetch`로 불러오는 방식으로 분리하여 코드 중복을 줄이고 재사용성을 높임

`간단한 동적 기능 구현`
- `setInterval`, `DOM` 조작 등을 통해 실시간 타이머 구현     
- 사용자 인터랙션을 위한 `JS` 흐름을 실습함  

<br/>

### Schedule
- 2025.05.12. - 2025.05.23.

<br/>

## Tech Stack
**Design / Prototyping** 
- Figma
- Notion
  
**Frontend** 
- HTML
- SCSS (CSS Preprocessor)
- JavaScript

**Development Environment** 
- VS Code

**Deployment / CI**
- GitHub Pages  

<br/>

## Features
### Core Feature
`공통 레이아웃 분리 및 불러오기`
- Header와 Footer를 각각 `HTML` 파일로 저장하고 `fetch`를 사용해 불러오는 구조로 구현
- 반복되는 구조를 분리해 코드 유지보수성과 재사용성을 높임
- 이후 프로젝트에서 효율적으로 활용할 수 있는 구조 설계 연습

`동적 타이머 구현`
- setInterval`과 `DOM` 조작을 통해 실시간으로 시간이 흐르는 타이머 구현
- 시간 기반 DOM 업데이트 흐름을 학습하고 적용
- 간단한 동적 기능을 구현하며 JavaScript에 대한 이해도 향상

<br/>

### [Main Page](https://dkssud-dus.github.io/cloneCoding-Class101/index.html)

<details>
  <summary>Click to expand</summary>

<br/>

![1](https://github.com/user-attachments/assets/b76aeb8c-86bd-48db-ba7a-70cf77b09145)

**Purpose**
- 공통 컴포넌트 제작 및 사용법을 학습한다.
- 타이머 기능을 학습한다.
- 정적인 Main Page의 일관된 레이아웃을 학습한다.

**Summary**
- `fetch`를 활용해 Header와 Footer를 관리할 수 있도록 하였다.
- `setInterval`을 활용한 타이머 기능을 구현할 수 있도록 하였다.
- `flex`를 활용해 레이아웃을 작성하였다.
- `로그인` 버튼 클릭시 실제로 로그인이 된 것처럼 구현해, 사이트 회원이 볼 수 있는 Header 또한 구현해 보았다.
- 회원 가입 버튼 클릭 시 Sign Up 서브 페이지로 이동 가능하다.
- 진행 중인 이벤트 클릭 시 Course List 서브 페이지로 이동 가능하다.
- 오늘의 Best 클래스 클릭 시 Course Detail 서브 페이지로 이동 가능하다.

<br/>

</details>

<br/>

### [Sub Page: Sign Up](https://dkssud-dus.github.io/cloneCoding-Class101/html/member-register.html)

<details>
  <summary>Click to expand</summary>

<br/>

![5](https://github.com/user-attachments/assets/b2fe88ba-82a4-4e5a-a479-15579d28c6fc)

**Summary**
- `input`을 활용해 로그인 화면을 구현해 보았다.

<br/>

</details>

<br/>

### [Sub Page: Course List](https://dkssud-dus.github.io/cloneCoding-Class101/html/category-main.html)

<details>
  <summary>Click to expand</summary>

<br/>

![2](https://github.com/user-attachments/assets/1c392c6b-fd2d-41f9-b148-585e8570514f)

**Summary**
- Main Page에서 활용하였던 컴포넌트를 다시 활용할 수 있도록 하였다.
- 강의 클릭 시 Course Detail 서브 페이지로 이동 가능하다.

<br/>

</details>

<br/>

### [Sub Page: Course Detail](https://dkssud-dus.github.io/cloneCoding-Class101/html/class-detail.html)

<details>
  <summary>Click to expand</summary>

<br/>

![3](https://github.com/user-attachments/assets/493bada7-89ec-48b7-9806-5e970526f660)

**Summary**
- 각각 다른 디자인의 아코디언 메뉴를 구현해 볼 수 있도록 하였다.
- 수강 신청 버튼 클릭 시 Shopping 서브 페이지로 이동 가능하다.

<br/>

</details>

<br/>

### [Sub Page: Shopping](https://dkssud-dus.github.io/cloneCoding-Class101/html/take-course.html)

<details>
  <summary>Click to expand</summary>

<br/>

![4](https://github.com/user-attachments/assets/cdb2f1e7-5d2f-4489-84a2-c3a6a85361b8)

**Summary**
- `input`의 `checkbox` 속성을 활용해 볼 수 있도록 하였다.
- 쇼핑몰의 장바구니 레이아웃을 활용해 볼 수 있도록 하였다.

<br/>

</details>

<br/>

## Environment & Contribution
- OS: Windows 11, Windows 10
- Viewpoint: Desktop(1980px), Tablet(1024px), Mobile(767px)
- Contribute: 100% 개인 작업 (기획, 디자인, 개발)

<br/>

## Contact
- GitHub: https://github.com/dkssud-dus
- Email: chae3929@gmail.com
- LinkedIn: https://www.linkedin.com/in/dkssud-chaeyeon/


<br/><br/><br/>
