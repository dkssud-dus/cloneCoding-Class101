
---
`#CloneCoding` `#Solo` `#Desktop` `#Tablet` `#Mobile` `#Responsive`         
# **Website Clone Coding Project Details:**
### 클래스 101 Class 101

<br/>
<br/>
<br/>

**김채연, Kim chae yeon**    

<br/>
<br/>
<br/>

## Table of Contents

1. [Project Overview](#1-Project-Overview)   
2. [Core Features](#2-Core-Features)   
3. [Page-wise Features](#3-Page-wise-Features)    
   
</br>
</br>
</br>

---

## 1. Project Overview
### 1.1. Background
클래스 101은 다양한 분야의 지식이나 스킬을 유료로 구매하거나 구독하여 강의를 학습할 수 있는 플랫폼이다.

</br>

이 프로젝트의 목적은 다음과 같다.

</br>

1. `HTML` 구조화에 대해 연습한다.
2. 레이아웃 설계에 대해 연습한다.
3. `fetch` 등 `JS`의 주요 기능을 학습하고, 다음 프로젝트에 연계될 수 있도록 한다.

</br>
</br>
</br>

### 1.2. Keywords
1. **레이아웃 설계**        
    1.1. `Flex` 를 활용한 구조적 페이지 배치          
    
</br>

2. **컴포넌트 재사용**     
    2.1. Header/Footer를 `fetch`로 불러오는 방식으로 분리하여 코드 중복을 줄이고 재사용성을 높임
    
</br>

3. **간단한 동적 기능 구현**    
    3.1. `setInterval`, `DOM` 조작 등을 통해 실시간 타이머 구현     
    3.2. 사용자 인터랙션을 위한 `JS` 흐름을 실습함     
    

</br>
</br>
</br>

---

## 2. Core Features
### 공통 레이아웃 분리 및 불러오기
1. Header와 Footer를 각각 `HTML` 파일로 저장하고 `fetch`를 사용해 불러오는 구조로 구현
2. 반복되는 구조를 분리해 코드 유지보수성과 재사용성을 높임
3. 이후 프로젝트에서 효율적으로 활용할 수 있는 구조 설계 연습
   
</br>
</br>
</br>

### 동적 타이머 구현
1. `setInterval`과 `DOM` 조작을 통해 실시간으로 시간이 흐르는 타이머 구현
2. 시간 기반 DOM 업데이트 흐름을 학습하고 적용
3. 간단한 동적 기능을 구현하며 JavaScript에 대한 이해도 향상
   
</br>
</br>
</br>

---

## 3. Page-wise Features

### 3.1. [Main Page](https://dkssud-dus.github.io/cloneCoding-Class101/index.html)
![1](https://github.com/user-attachments/assets/b76aeb8c-86bd-48db-ba7a-70cf77b09145)

<br/>

#### 목적        
1. 공통 컴포넌트 제작 및 사용법을 학습한다.
2. 타이머 기능을 학습한다.
3. 정적인 Main Page의 일관된 레이아웃을 학습한다.

<br/>
   
#### 구현 요약 
1. `fetch`를 활용해 Header와 Footer를 관리할 수 있도록 하였다.
2. `setInterval`을 활용한 타이머 기능을 구현할 수 있도록 하였다.
3. `flex`를 활용해 레이아웃을 작성하였다.
4. `로그인` 버튼 클릭시 실제로 로그인이 된 것처럼 구현해, 사이트 회원이 볼 수 있는 Header 또한 구현해 보았다.
5. 회원 가입 버튼 클릭 시 Sign Up 서브 페이지로 이동 가능하다.
6. 진행 중인 이벤트 클릭 시 Course List 서브 페이지로 이동 가능하다.
7. 오늘의 Best 클래스 클릭 시 Course Detail 서브 페이지로 이동 가능하다.

<br/>
<br/>
<br/>

---

### 3.2. Sub Pages (4)

---

### 3.2.1. Sign Up
![5](https://github.com/user-attachments/assets/b2fe88ba-82a4-4e5a-a479-15579d28c6fc)

<br/>

#### 구현 요약
1. `input`을 활용해 로그인 화면을 구현해 보았다.

</br>
</br>
</br>

### 3.2.2. Course List
![2](https://github.com/user-attachments/assets/1c392c6b-fd2d-41f9-b148-585e8570514f)

<br/>

#### 구현 요약
1. Main Page에서 활용하였던 컴포넌트를 다시 활용할 수 있도록 하였다.
2. 강의 클릭 시 Course Detail 서브 페이지로 이동 가능하다.

</br>
</br>
</br>

### 3.2.3. Course Detail
![3](https://github.com/user-attachments/assets/493bada7-89ec-48b7-9806-5e970526f660)

<br/>

#### 구현 요약
1. 각각 다른 디자인의 아코디언 메뉴를 구현해 볼 수 있도록 하였다.
2. 수강 신청 버튼 클릭 시 Shopping 서브 페이지로 이동 가능하다.

</br>
</br>
</br>

### 3.2.4. Shopping
![4](https://github.com/user-attachments/assets/cdb2f1e7-5d2f-4489-84a2-c3a6a85361b8)

<br/>

#### 구현 요약
1. `input`의 `checkbox` 속성을 활용해 볼 수 있도록 하였다.
2. 쇼핑몰의 장바구니 레이아웃을 활용해 볼 수 있도록 하였다.

</br>
</br>
</br>

---
