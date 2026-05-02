## 프로젝트 소개
Spring Boot 기반 프로젝트를 빠르게 시작할 수 있는 스타터 킷입니다.

## 기술 스택
- Java 17
- Spring Boot 3.5.14
- Spring Security
- Spring Data JPA
- Swagger (springdoc-openapi)
- Lombok

## 디렉토리 구조
```
src
├── common
│   ├── response
│   ├── exception
│   └── entity
├── config
└── domain
```

## 실행 방법
1. application-local.yml.example을 application-local.yml로 복사
2. ./gradlew bootRun

## 환경변수 설명
| 변수명 | 설명 |
|--------|------|
| DB_URL | 데이터베이스 URL |