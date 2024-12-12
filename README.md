# KigBoard

KigBoard는 회원 관리 기능과 간단한 게시판 CRUD 기능을 포함하는 예제 Spring Boot 프로젝트입니다. 이 프로젝트는 Spring Boot, Spring Security, H2 Database, Spring Data JPA, Thymeleaf를 사용하여 구현되었습니다.

## 프로젝트 목적

이 프로젝트는 다음과 같은 기능을 제공합니다:
- 회원가입 및 로그인 기능 (Spring Security 사용)
- 게시판 CRUD 기능 (생성, 읽기, 수정, 삭제)

## 설치 및 실행 방법

### 요구사항
- Java 11 이상
- Maven 또는 Gradle

### 설치 방법

1. 리포지토리를 클론합니다.
    ```bash
    git clone https://github.com/yourusername/kigboard.git
    cd kigboard
    ```

2. 필요한 의존성을 설치합니다.
    ```bash
    mvn install
    ```
    또는
    ```bash
    ./gradlew build
    ```

3. 애플리케이션을 실행합니다.
    ```bash
    mvn spring-boot:run
    ```
    또는
    ```bash
    ./gradlew bootRun
    ```

### 기본 설정

- 애플리케이션은 기본적으로 `http://localhost:8080`에서 실행됩니다.
- H2 데이터베이스 콘솔은 `http://localhost:8080/h2-console`에서 접근할 수 있습니다.
    - JDBC URL: `jdbc:h2:mem:testdb`
    - User Name: `sa`
    - Password: (비워둡니다)

## 사용법

1. 애플리케이션이 실행되면, 브라우저를 열고 `http://localhost:8080`으로 이동합니다.
2. 회원가입 페이지에서 새로운 사용자를 등록합니다.
3. 등록한 사용자 정보로 로그인합니다.
4. 게시판 페이지에서 게시글을 작성하고 관리합니다.

## 기여 방법

이 프로젝트에 기여하고 싶다면, 다음 단계를 따라 주세요:

1. 리포지토리를 포크합니다.
2. 새로운 브랜치를 생성합니다 (`git checkout -b feature/새로운기능`).
3. 변경 사항을 커밋합니다 (`git commit -m '새로운 기능 추가'`).
4. 브랜치에 푸시합니다 (`git push origin feature/새로운기능`).
5. 풀 리퀘스트를 만듭니다.

## 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

---
