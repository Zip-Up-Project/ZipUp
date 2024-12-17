# ZipUp

## 프로젝트 개요

프론트엔드와 백엔드을 공부하기 위한 간단한 온라인 쇼핑몰 팀 프로젝트입니다.  
Spring Boot를 기반으로 백엔드를 구축하며 HTML, CSS, JavaScript로 프론트엔드를 구성합니다.

## 주요 기능

1. **회원가입 및 로그인**

   - 사용자와 판매자로 역할(role) 구분

2. **상품 관리**
   - **상품 리스트** : 메인 페이지에서 카테고리별 상품 보기
   - **상품 상세** : 이미지, 상품명, 가격, 옵션(사이즈, 색상 등), 상품 설명 표시
   - **상품 등록** : 판매자 전용 기능

## 기술 스택


### **개발 환경**  
- **JDK 17**  
- **Maven 3.x**  
- **VSCode**

### 프론트엔드

- **HTML**, **CSS**, **JavaScript**

### 백엔드

- **Spring Boot**

### 데이터베이스

- **MySQL**

## 브랜치 관리 규칙

- **`main`**

  - 최종 배포 가능한 코드만 존재합니다.
  - 직접 커밋은 금지되며, **Pull Request (PR)**를 통해서만 병합됩니다.

- **`develop`**

  - 현재 개발 중인 코드가 모이는 브랜치입니다.
  - 모든 작업 브랜치는 `develop`에서 시작합니다.

- **작업 브랜치**
  - 브랜치 이름은 **작업 유형/세부 내용**으로 작성합니다.
  - 예시:
    - 신규 기능 : `feature/front/작업내용`
    - 버그 수정 : `fix/back/버그수정내용`


 ## 백엔드 실행

 mvn install
 
 mvn spring-boot:run

## **백엔드 환경변수 설정**

### MAC
export DB_URL=jdbc:mysql://localhost:3306/zipup

export DB_USERNAME=your-username

export DB_PASSWORD=your-password

### Window
set DB_URL=jdbc:mysql://localhost:3306/zipup

set DB_USERNAME=your-username

set DB_PASSWORD=your-password


