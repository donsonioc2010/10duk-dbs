# 10duk-dbs-be

## Index

## 개요
> **Note**  
> AVDbs 를 보면서 들었던 생각이 각종 서브 컬쳐에 대해서도 이런식으로의 표현 방법을 해보면 재밌지 않을까? 라는 생각을 하게되어 진행해보게 됨  
> 일단 *게임*에서부터 시작해볼 예정으로, 초기 목표는 *게임*, *애니메이션*, *E-Sports*, *인방*, *아이돌* 정도가 목표..?  
> MSA까지 해보고자 하였는데, 혼자하기엔 너무 커진다 생각해서 모놀리식으로 개발은 하지만, Multi Module방식으로 변경해볼 예정이다.

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
> **Warning** : 일단 Next.js는 React써보고싶어서 해보게 된계기, 무조건 해볼예정인데 세부적인건 정하질 않음.
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
    > **Note**
    > dbdocs/10duk_dbs.dbml 파일의 스키마 구조를 참고하여 자동배포를 진행한다   
    > 해당파일을 수정하고 `main`또는 `develop`브랜치를 수정할 경우 문서가 변경된다.  
    > DBDOCS_PROJECT, DBDOCS_TOKEN의 경우에는 모두 Git Action Sedrets에 등록된 상황.

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