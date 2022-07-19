# Guest-Book-Practice
Spring MVC &amp; Spring Data JPA &amp; Thymeleaf &amp; MariaDB



## Goal
- 전체적인 구조를 실습하면서 테이블이 하나로만 구성되는 '방명록(Guest Book)'을 구성하였습니다.
- 해당 프로젝트는 하나의 엔티티 클래스를 이용해서 CRUD 기능과 검색/페이징 기능을 가지는 웹 애플리케이션을 제작하였습니다.

  - 프로젝트의 계층별 구조와 객체들의 구성
  - Querydsl을 이용해서 동적으로 검색 조건을 처리하는 방법
  - Entity 객체와 DTO의 구분
  - 화면에서의 페이징 처리


## Spec
- Java 11
- Spring Boot (v2.7.1)
- Spring Data JPA
- IntelliJ IDEA CE
- MariaDB (v3.0.6)


## Spring Initializr - Selected Dependencies

### Developer Tools
- Spring Boot DevTools
- Lombok

### Web
- Spring Web

### Template Engins
- Thymeleaf

### SQL
- Spring Data JPA


## IntelliJ IDEA CE
- Gradle Setting
  
    <img width="700" alt="guest-book-practice-gradle-setting" src="https://user-images.githubusercontent.com/83820185/179662416-c4b222c4-b1bb-476a-8421-991a33e6b0e4.png">

  

## Guestbook page
- http://localhost:8080/guestbook/list

  <img width="1000" alt="guestbook_page" src="https://user-images.githubusercontent.com/83820185/179460599-f2d529f0-3dc4-4d2e-9664-fd52e9994686.png">


