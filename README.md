# 10duk-dbs-be

## Index

## 개요
> **Note**
> AvDbs를 보면서 

---

## Develop Setting

### BackEnd
- **Spring**
  - `Boot`
  - `Security` + `JWT`
  - `JPA` + `querydsl`
  - `Actuator`
  - `cloud(AWS)`
  - `Mail` + `thymeleaf` + `common-io`
  - `mariadb-connector`
  - `redis`
  - **Docs**
    - `Swagger`
    - `Spring Rest Docs`
  - **APM**
    - `Prometheus` + `Grafana`
  - **MQ**
    - `Kafka`

### Front
- Next.js

### DataBase
- **MariaDB**
- **Redis**
- **Docs**
  - DBDiagram
    - [다이어그램 링크](https://dbdiagram.io/d/63fc4c52296d97641d83e97d)
    - 수정 희망시 연락바람
  - DB Docs
    - [문서화 링크](https://dbdocs.io/donsonioc2010/10duk_dbs)
    - dbdocs/10duk_dbs.dbml참조
      - 해당 파일을 갱신하는 경우 문서화된 파일이 자동 배포된다.
      - DBDOCS_PROJECT, DBDOCS_TOKEN은 모두 Git Action Sedrets에 등록된 상황.

### ETC
- **CodeStyle**
  - Google Java Style Code - Gradle에서 설정예정.
- Project-Structure
  - multi-module 방식으로 진행해볼 예정

---

## Architecture Structure
> 아키텍처 구상도 삽입 예정

---

## End Points List
| URL     | Request Type | Description |
|:--------|:------------:|:------------|
| /Sample |    `GET`     | 테이블 샘플 제작용  |

---

## 이슈 리스트