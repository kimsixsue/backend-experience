# Backend Experience Portfolio

Python·FastAPI 기반 REST API 개발, MongoDB 기반 데이터 조회·처리, MQTT 수집 데이터 흐름 검증, Linux·Docker·NGINX 운영 환경 확인 경험을 정리한 백엔드 실무 포트폴리오입니다.

본 저장소는 회사 내부 소스코드나 기밀 정보를 공개하지 않고, 외부에 설명 가능한 범위에서 담당 업무, 사용 기술, 문제 해결 경험, 문서화 경험을 정리하기 위한 목적으로 작성했습니다.

---

## Summary

저는 API, DB, 데이터 수집 흐름, 운영 환경을 함께 이해하는 백엔드/서버 개발자로 성장하고 있습니다.

현재 ㈜타오스에서 AI 기반 EV 배터리 모니터링 솔루션 R&D 과제에 참여하며 Python·FastAPI 기반 REST API 구현, MongoDB 기반 차량·센서·리포트 데이터 조회·처리, MQTT 수집 데이터 흐름 확인, Linux·Docker·NGINX 기반 운영 이슈 재현 및 문서화를 수행하고 있습니다.

이전에는 ㈜사랑넷에서 스마트HACCP SaaS 서비스와 사내 인트라넷 운영·유지보수를 담당하며 PHP 기반 기능 수정, MySQL/MariaDB 데이터 관리, Linux 서버 운영 지원, 관리자 화면 오류 대응을 경험했습니다.

---

## Core Experience

| Area          | Experience                                               |
| ------------- | -------------------------------------------------------- |
| Backend API   | Python·FastAPI 기반 REST API 엔드포인트 구현, PHP 기반 운영 서비스 기능 수정 |
| Database      | MongoDB 기반 데이터 조회·필터링·집계, MySQL/MariaDB 기반 데이터 조회·수정·관리  |
| Data Flow     | MQTT 수집 데이터, DB 저장 데이터, API 응답, 화면 표시값 간 데이터 흐름 확인       |
| Operation     | Linux·Docker·NGINX 환경에서 API 오류, 데이터 불일치, 운영 이슈 재현        |
| Documentation | 운영 설정, 오류 대응 절차, 인수인계 문서, 기술 참고 문서 작성                    |
| Maintenance   | 운영 중인 웹서비스 기능 오류, DB 데이터 오류, 관리자 화면 표시 문제 대응             |

---

# 1. AI 기반 EV 배터리 모니터링 솔루션 연구개발

## Overview

* Company: ㈜타오스
* Period: 2026.01 ~ Present
* Role: Backend / Server Developer
* Domain: EV Battery Monitoring, IoT Data, AI Report Integration
* Main Stack: Python, FastAPI, REST API, MongoDB, MQTT, Linux, Docker, NGINX, Git

AI 기반 EV 배터리 모니터링 솔루션 R&D 과제에서 백엔드 API 개발과 데이터 처리 기능을 담당하고 있습니다.

차량·센서·리포트 데이터를 조회하고, MQTT 기반으로 수집된 데이터가 DB에 저장된 뒤 API 응답을 거쳐 모니터링 화면에 표시되는 흐름을 확인합니다. 또한 AI 분석 결과 및 예측 리포트 데이터 연동 흐름을 검증하고, 운영 환경에서 발생하는 API 오류와 데이터 불일치 이슈를 재현하며 문서화하고 있습니다.

---

## Responsibilities

* Python·FastAPI 기반 REST API 엔드포인트 구현
* API 응답 데이터 구조 확인 및 처리
* MongoDB 기반 차량·센서·리포트 데이터 조회 로직 구현
* 데이터 필터링, 집계, 응답 변환 로직 확인 및 개선
* MQTT 수집 데이터와 DB 저장 데이터 간 흐름 확인
* DB 조회 결과, API 응답, 모니터링 화면 표시값 간 불일치 확인
* AI 분석 결과 및 예측 리포트 데이터 연동 흐름 검증
* API 오류, 데이터 불일치, 운영 이슈 재현
* Linux·Docker 환경에서 백엔드 서비스 실행 상태 확인
* NGINX·HTTPS/SSL 등 운영 환경 관련 설정 확인 및 문서화
* 서버·백엔드·DB·운영 구조에 대한 인수인계 문서 작성
* R&D 과제 관련 기술 자료 조사 및 개발 문서 정리

---

## Backend API Experience

FastAPI 기반 REST API를 구현하며, 단순히 엔드포인트를 만드는 것뿐 아니라 DB 조회 결과가 실제 서비스 화면에서 사용할 수 있는 응답 구조로 전달되는 흐름을 함께 확인했습니다.

주요 경험은 다음과 같습니다.

* 요청 파라미터에 따른 데이터 조회 처리
* 차량, 센서, 리포트 관련 데이터 응답 구성
* MongoDB 조회 결과를 API 응답 형태로 변환
* API 응답 구조와 프론트 화면 표시값 간 불일치 확인
* 누락값, 빈 값, 예상과 다른 데이터 형식 확인
* 기능 검증 과정에서 API 오류 재현 및 원인 파악 지원

---

## MongoDB Data Processing Experience

MongoDB 기반 데이터 조회·처리 업무를 수행하며 차량·센서·리포트 데이터의 조회 조건, 필터링, 집계 흐름을 다뤘습니다.

주요 경험은 다음과 같습니다.

* 차량 단위 데이터 조회
* 센서 데이터 조회 및 조건별 필터링
* 리포트 데이터 조회 및 응답 구조 확인
* 수집 데이터와 저장 데이터 간 불일치 확인
* API 응답에 필요한 데이터 가공 흐름 확인
* 데이터 누락, 중복, 불일치 상황 확인 및 검증

---

## MQTT Data Flow Verification

MQTT 기반으로 수집되는 데이터가 서비스에서 어떻게 활용되는지 확인하며, 수집 데이터와 DB 저장 데이터, API 응답, 화면 표시값 간 연결 흐름을 검증했습니다.

주요 확인 흐름은 다음과 같습니다.

```text
MQTT 수집 데이터
        ↓
Database 저장 데이터
        ↓
Backend API 응답
        ↓
Monitoring 화면 표시값
```

이 과정에서 단순히 API 응답만 확인하는 것이 아니라, 데이터가 수집되고 저장되고 조회되어 화면에 표시되는 전체 흐름을 기준으로 문제를 확인했습니다.

---

## Operation & Infrastructure Experience

Linux·Docker·NGINX 기반 운영 환경에서 서비스 상태를 확인하고, API 오류와 운영 이슈를 재현하며, 확인 절차와 대응 내용을 문서로 정리했습니다.

주요 경험은 다음과 같습니다.

* Linux 환경에서 서비스 실행 상태 확인
* Docker 기반 서비스 실행 및 운영 상태 확인
* NGINX 설정 확인
* HTTPS/SSL 관련 운영 설정 확인
* API 오류 및 운영 이슈 재현
* 서비스 설정, 배포 구조, 운영 참고 내용 문서화
* 후속 담당자를 위한 인수인계 문서 작성

---

## Documentation Experience

운영 환경과 백엔드 구조를 후속 담당자가 이해할 수 있도록 문서화하는 업무를 수행했습니다.

작성한 문서의 성격은 다음과 같습니다.

* 백엔드 서비스 구조 정리
* API 관련 확인 절차 정리
* 서버 및 운영 환경 참고 문서 작성
* NGINX·HTTPS/SSL 설정 관련 문서 정리
* 오류 재현 및 확인 절차 문서화
* 인수인계 문서 작성
* R&D 과제 관련 기술 자료 조사 및 정리

회사 내부 정보 보호를 위해 실제 소스코드, API 명세, 서버 접속 정보, 계정 정보, DB 구조, 고객 정보는 포함하지 않았습니다.

---

# 2. 스마트HACCP SaaS 및 사내 인트라넷 운영·유지보수

## Overview

* Company: ㈜사랑넷
* Period: 2023.11 ~ 2025.07
* Role: Backend / Server Developer
* Domain: SmartHACCP SaaS, Intranet, Web Service Maintenance
* Main Stack: PHP, MySQL, MariaDB, SQL, Linux, JavaScript, jQuery, Ajax, HTML, CSS, Bootstrap

스마트HACCP SaaS 서비스와 사내 인트라넷의 운영·유지보수 업무를 담당했습니다.

PHP 기반 운영 서비스의 기능 수정, MySQL/MariaDB 기반 데이터 조회·수정·관리, Linux 서버 환경에서의 서비스 상태 확인, JavaScript·jQuery·Ajax 기반 관리자 화면 오류 대응을 수행했습니다.

---

## Responsibilities

* 스마트HACCP SaaS 서비스 운영·유지보수
* 사내 인트라넷 운영·유지보수
* PHP 기반 백엔드 기능 수정 및 오류 대응
* MySQL/MariaDB 기반 데이터 조회·수정·관리
* SQL을 활용한 운영 데이터 확인
* Linux 서버 환경에서 서비스 상태 확인
* JavaScript·jQuery·Ajax 기반 관리자 화면 기능 개선
* HTML·CSS·Bootstrap 기반 관리자 페이지 유지보수
* 운영 중인 서비스의 기능 오류, DB 데이터 오류, 화면 표시 문제 확인 및 대응

---

## PHP Backend Maintenance Experience

운영 중인 PHP 기반 웹서비스에서 기능 수정과 오류 대응 업무를 수행했습니다.

주요 경험은 다음과 같습니다.

* 기존 PHP 코드 기반 기능 수정
* 운영 서비스 백엔드 오류 확인
* 관리자 화면 기능 동작과 백엔드 처리 결과 확인
* 기능 수정 후 화면 표시값 및 DB 데이터 확인
* 운영 중 발생한 오류의 원인 확인 및 수정 지원

---

## MySQL / MariaDB Data Management Experience

MySQL/MariaDB 기반 운영 데이터를 조회·수정·관리하며, 서비스 화면과 DB 데이터 간 불일치 문제를 확인했습니다.

주요 경험은 다음과 같습니다.

* SQL 기반 운영 데이터 조회
* MySQL/MariaDB 데이터 수정 및 관리
* 관리자 화면 표시값과 DB 데이터 비교
* 기능 오류 발생 시 관련 데이터 확인
* 운영 데이터 정합성 확인

---

## Frontend Maintenance Experience

관리자 화면과 서비스 화면의 유지보수 과정에서 JavaScript, jQuery, Ajax, HTML, CSS, Bootstrap을 활용했습니다.

주요 경험은 다음과 같습니다.

* JavaScript·jQuery 기반 화면 기능 수정
* Ajax 요청·응답 흐름 확인
* 관리자 화면 오류 대응
* HTML·CSS·Bootstrap 기반 화면 유지보수
* 화면 표시값과 백엔드 처리 결과 간 불일치 확인

---

## Service Operation Experience

운영 중인 웹서비스를 유지보수하며 기능, DB, 화면, 서버 환경을 함께 확인하는 경험을 쌓았습니다.

주요 경험은 다음과 같습니다.

* 운영 서비스 기능 오류 확인
* DB 데이터 문제 확인
* 관리자 화면 표시 문제 대응
* Linux 서버 환경에서 서비스 상태 확인
* 서비스 운영 중 발생하는 이슈 대응
* 오류 원인 확인과 재발 방지를 고려한 유지보수 경험

---

# 3. Experience Map

## Backend

* Python 기반 API 개발
* FastAPI 기반 REST API 구현
* PHP 기반 운영 서비스 기능 수정
* API 요청·응답 흐름 확인
* 백엔드 오류 재현 및 원인 파악 지원

## Database

* MongoDB 기반 데이터 조회·필터링·집계
* MySQL/MariaDB 기반 데이터 조회·수정·관리
* SQL 기반 운영 데이터 확인
* API 응답과 DB 데이터 간 정합성 확인

## Data Flow

* MQTT 수집 데이터 흐름 확인
* DB 저장 데이터 확인
* API 응답 데이터 확인
* 화면 표시값 확인
* 데이터 불일치 원인 파악 지원

## Operation

* Linux 환경 서비스 상태 확인
* Docker 기반 운영 환경 확인
* NGINX 설정 확인
* HTTPS/SSL 관련 운영 설정 확인
* 운영 이슈 재현 및 확인 절차 문서화

## Documentation

* 운영 참고 문서 작성
* 인수인계 문서 작성
* 오류 대응 절차 정리
* 기술 자료 조사 및 정리
* 서비스 구조와 운영 환경 설명 문서 작성

---

# 4. Technical Keywords

## Currently Used

* Python
* FastAPI
* REST API
* MongoDB
* MQTT
* Linux
* Docker
* NGINX
* Git

## Previously Used

* PHP
* MySQL
* MariaDB
* SQL
* JavaScript
* jQuery
* Ajax
* HTML
* CSS
* Bootstrap

## Learning / Transferable Areas

* PostgreSQL
* Flask
* Elasticsearch
* Redis
* Cloud Environment
* AI API Integration
* LLM / ML Model Integration

위 항목들은 현재 또는 이전 업무에서 직접 사용한 기술과, 기존 경험을 바탕으로 빠르게 적응 가능한 기술 영역을 구분하기 위해 작성했습니다.

---

# 5. What I Focus On

저는 백엔드 개발을 단순히 API 엔드포인트 구현으로만 보지 않고, 다음 흐름을 함께 확인하는 방식으로 업무를 수행하고 있습니다.

```text
Data Collection
        ↓
Database
        ↓
Backend API
        ↓
Frontend / Monitoring Screen
        ↓
Operation & Maintenance
```

특히 다음과 같은 부분을 중요하게 생각합니다.

* API 응답 구조가 실제 화면 요구사항과 맞는지 확인
* DB 조회 결과와 화면 표시값이 일치하는지 확인
* 수집 데이터가 서비스에서 올바르게 활용되는지 확인
* 운영 환경에서 발생하는 오류를 재현하고 문서화
* 후속 유지보수를 고려한 문서 작성
* 회사 기밀을 보호하면서 외부에 설명 가능한 수준으로 경험 정리

---

# 6. Security Notice

본 저장소는 실무 경험 요약용 포트폴리오입니다.

다음 정보는 포함하지 않습니다.

* 회사 내부 소스코드
* 실제 API 명세
* 데이터베이스 구조
* 서버 접속 정보
* 계정 정보
* 고객 정보
* 비공개 프로젝트 자료
* 회사 내부 문서
* 기밀 데이터

모든 내용은 외부 공개 가능한 범위에서 작성했습니다.

---

# 7. Contact

* GitHub: https://github.com/kimsixsue
* LinkedIn: https://www.linkedin.com/in/kimsixsue/
* Profile README: https://github.com/kimsixsue/kimsixsue
