# backend-experience

회사 기밀을 제외하고 PHP 기반 웹서비스 운영·유지보수, REST API 개발, DB 데이터 처리, 웹/API 헬스체크 모니터링, Linux·Docker·NGINX 운영 이슈 대응, 문서화 경험을 정리한 백엔드 포트폴리오입니다.

이전에는 PHP, MySQL/MariaDB, Linux 기반 스마트HACCP SaaS 및 사내 인트라넷 운영·유지보수를 담당하며 기능 수정, DB 조회·수정·관리, 관리자 화면 오류 대응, 서비스 상태 확인 업무를 수행했습니다.

현재는 Python·FastAPI 기반 REST API 개발, MongoDB 기반 데이터 조회·처리, MQTT 수집 데이터 흐름 확인, 웹/API 헬스체크 모니터링 운영, Linux·Docker·NGINX 운영 환경 확인 업무를 수행하고 있습니다.

실제 회사 내부 소스코드, API 명세, DB 구조 원문, 서버 정보, 계정 정보, 운영 문서 원문은 포함하지 않으며, 외부에 설명 가능한 범위에서 담당 업무와 기술 경험을 정리했습니다.

---

## Core Summary

| Area            | Experience                                     |
| --------------- | ---------------------------------------------- |
| Web Maintenance | PHP 기반 웹서비스 운영·유지보수, 기능 수정, 관리자 화면 오류 대응       |
| Database        | MySQL/MariaDB 조회·수정·관리, MongoDB 조회·필터링·집계      |
| REST API        | Python·FastAPI 기반 API 구현, 응답 데이터 구조 정리         |
| Data Flow       | DB 저장 데이터, API 응답, 화면 표시값 흐름 검증                |
| Monitoring      | Python 기반 웹/API 헬스체크, HTTP 상태·응답 지연·데이터 신선도 확인 |
| Operation       | Linux·Docker·NGINX 환경에서 운영 이슈 확인 및 오류 재현       |
| Documentation   | 운영 참고 문서, 오류 대응 기록, 기술 자료, 인수인계 문서 작성          |

---

# Core Experience

## 1. PHP / MySQL Maintenance

이전 직장에서 수행한 PHP, MySQL/MariaDB 기반 웹서비스 운영·유지보수 경험을 정리했습니다.

* 스마트HACCP SaaS 및 사내 인트라넷 운영·유지보수
* PHP 기반 운영 서비스 기능 수정
* 백엔드 오류 대응
* MySQL/MariaDB 데이터 조회·수정·관리
* 운영 중인 웹서비스 오류 대응
* 관리자 화면 표시값, DB 데이터, PHP 백엔드 처리 결과 비교
* Linux 서버 환경에서 서비스 상태 확인

---

## 2. REST API Development

Python·FastAPI 기반 REST API 기능 개발 경험을 정리했습니다.

* REST API 엔드포인트 구현
* 요청 파라미터 처리
* API 응답 데이터 구조 정리
* DB 조회 결과를 API 응답 형태로 변환
* API 응답 구조 확인
* 기능 검증 및 오류 재현
* API 응답과 화면 표시 데이터 간 흐름 확인

---

## 3. MongoDB Data Processing

MongoDB 기반 차량·센서·리포트 데이터 조회 및 처리 경험을 정리했습니다.

* 차량 데이터 조회
* 센서 데이터 조회
* 리포트 데이터 조회
* 조건 기반 필터링
* 집계 로직 구현 및 확인
* DB 조회 결과와 API 응답 데이터 비교
* 데이터 누락·불일치 원인 확인

---

## 4. Web/API Health Check Monitoring

Python 기반 웹/API 헬스체크 모니터링 프로세스를 운영하며 서비스 상태 확인 흐름을 관리한 경험을 정리했습니다.

* 웹/API 엔드포인트 상태 확인
* HTTP 상태 확인
* 응답 지연 확인
* 데이터 수집 신선도 확인
* 장애 알림 흐름 관리
* 정기 리포트 흐름 관리
* 운영 이슈 발생 시 확인 절차 정리
* 후속 유지보수를 위한 운영 참고 문서 작성

---

## 5. Linux / Docker / NGINX Operation

Linux·Docker·NGINX 기반 운영 환경에서 서비스 상태를 확인하고 오류를 재현한 경험을 정리했습니다.

* Linux 환경에서 서비스 상태 확인
* Docker 기반 실행 환경 확인
* API 오류 및 운영 이슈 재현
* 데이터 불일치 상황 재현
* NGINX 설정 관련 이슈 확인
* HTTPS/SSL 운영 환경 확인
* 백업·복구 참고 절차 정리
* 운영 환경 관련 문서 정리
* 후속 유지보수를 위한 인수인계 문서 작성

---

## 6. MQTT Data Flow Verification

MQTT 기반 수집 데이터가 DB, API, 화면까지 연결되는 흐름을 확인한 경험을 정리했습니다.

```text
MQTT 수집 데이터
        ↓
DB 저장 데이터
        ↓
Backend API 응답
        ↓
Monitoring 화면 표시값
```

* MQTT 수집 데이터 흐름 확인
* 수집 데이터와 DB 저장 데이터 비교
* DB 조회 결과와 API 응답 데이터 비교
* API 응답 데이터와 모니터링 화면 표시값 비교
* 데이터 불일치 발생 시 원인 확인
* 기능 검증 및 운영 오류 재현

---

# Work Experience Details

## ㈜타오스

Backend / Server Developer
2026.01 ~ Present

AI 기반 EV 배터리 모니터링 솔루션 R&D 과제에서 Python·FastAPI 기반 백엔드 API 개발과 데이터 처리 기능을 담당하고 있습니다.

### 담당 업무

* Python·FastAPI 기반 REST API 엔드포인트 구현 및 응답 데이터 구조 정리
* MongoDB 기반 차량·센서·리포트 데이터 조회·필터링·집계 로직 구현
* MQTT 수집 데이터, DB 저장 데이터, API 응답, 모니터링 화면 표시값을 대조하여 데이터 흐름 검증
* AI 분석/예측 리포트 연동값의 누락·불일치 여부 확인 및 API 응답 구조 개선 지원
* Python 기반 웹/API 헬스체크 모니터링 프로세스 운영 및 상태 확인 흐름 관리
* HTTP 상태, 응답 지연, 데이터 수집 신선도 등 서비스 상태 점검 항목 확인
* 장애 알림 및 정기 리포트 흐름을 확인하며 운영 이슈 대응 과정 지원
* Linux·Docker·NGINX 환경에서 API 오류, 데이터 불일치, 운영 이슈 재현 및 원인 파악 지원
* HTTPS/SSL, NGINX, Docker, 백업·복구 참고 절차 등 운영 환경 관련 내용 정리
* 서비스 구조, 레포지토리 구성, 운영 설정, 오류 확인 절차를 후속 담당자가 이해할 수 있도록 인수인계 문서 작성
* Git 기반으로 기술 자료, 운영 참고 문서, 프로젝트별 인수인계 문서, R&D 과제 관련 업무 기록 정리 및 관리

### 기여 내용

* 차량·센서·리포트 데이터를 API 응답 형태로 제공하기 위한 MongoDB 조회·처리 흐름을 구현했습니다.
* MQTT 수집 데이터부터 DB 저장 데이터, API 응답, 화면 표시값까지 단계별로 대조하며 데이터 누락·불일치 원인 파악을 지원했습니다.
* AI 분석/예측 리포트 연동값이 화면과 API 응답에서 정상적으로 표시되는지 확인하고, 누락값·불일치 항목을 정리하여 응답 구조 개선을 지원했습니다.
* Python 기반 헬스체크 모니터링 프로세스를 관리하며 웹/API 엔드포인트 상태, 응답 지연, 데이터 수집 신선도, 장애 알림 흐름을 확인했습니다.
* Linux·Docker·NGINX 기반 운영 환경에서 발생한 API 오류와 데이터 불일치 상황을 재현하고, 확인 절차와 대응 내용을 문서화했습니다.
* NGINX, HTTPS/SSL, Docker 실행 구조, 백업·복구 참고 절차, 서비스별 운영 참고사항을 정리하여 후속 유지보수와 인수인계에 활용할 수 있도록 문서화했습니다.

---

## ㈜사랑넷

Backend / Server Developer
2023.11 ~ 2025.07

스마트HACCP SaaS 서비스와 사내 인트라넷 운영·유지보수를 담당했습니다.

### 담당 업무

* 스마트HACCP SaaS 서비스 및 사내 인트라넷 운영·유지보수
* PHP 기반 운영 서비스 기능 수정 및 백엔드 오류 대응
* MySQL/MariaDB 데이터 조회·수정·관리 및 운영 데이터 확인
* Linux 서버 환경에서 서비스 상태 확인 및 운영 이슈 대응
* JavaScript·jQuery·Ajax 기반 관리자 화면 기능 개선 및 오류 수정
* 관리자 화면 표시값, DB 데이터, PHP 백엔드 처리 결과를 비교하여 오류 원인 확인 및 수정 지원

### 기여 내용

* 운영 중인 웹서비스의 기능 오류, DB 데이터 문제, 관리자 화면 표시 문제를 함께 확인하며 서비스 유지보수 전반을 경험했습니다.
* PHP, MySQL/MariaDB, Linux 기반 운영 환경에서 백엔드 기능 수정, 데이터 관리, 서비스 상태 확인 역량을 쌓았습니다.
* 관리자 화면과 백엔드 처리 결과, DB 데이터를 함께 대조하며 화면 표시, 데이터 조회, 기능 동작 간의 연결 흐름을 이해했습니다.
* 운영 서비스에서 발생하는 오류를 단순 수정에 그치지 않고, 화면·DB·백엔드 처리 흐름을 함께 확인하며 원인 파악과 재발 방지를 고려해 대응했습니다.

---

# Education, Training, and Projects

## 삼성 청년 SW 아카데미

2022.07 ~ 2022.11

* Django 기반 웹 애플리케이션 개발 및 REST API 설계·구현 실습
* Python 서버사이드 로직 구현
* 외부 API 연동 및 DB 조회·관리
* Vue.js 프론트엔드와 연동한 서버-클라이언트 통신 테스트·디버깅
* 웹 서비스 구조, 관계형 DB 설계, API 요청·응답 흐름 학습

---

## 채용연계형 AI 개발자 양성 부트캠프

2025.07 ~ 2025.10

* Python 기반 데이터 수집·정제 스크립트 작성 및 반복 처리 자동화 실습
* 입력·출력 데이터 포맷 정의
* 전처리 결과 검증
* 오류 데이터 디버깅
* 데이터 수집·정제·저장·검증 흐름 구현

---

## 룸메이트 매칭 시스템 정보시스템 분석 보고서

* 요구사항 분석
* 일정 계획
* Context Diagram 작성
* ERD 및 데이터베이스 설계
* 화면 설계
* 시스템 구조 분석

---

## 국민청원 데이터 텍스트마이닝 프로젝트

* Python 기반 데이터 수집 및 전처리
* 텍스트 데이터 정리 및 분석
* 형태소 분석
* 감성분석
* 문서 클러스터링
* 문서 분류
* 토픽 모델링

---

# Tech Stack

| Area                   | Stack                                                    |
| ---------------------- | -------------------------------------------------------- |
| Backend                | PHP · Python · FastAPI · REST API                        |
| Database               | MySQL · MariaDB · SQL · MongoDB                          |
| Server / Infra         | Linux · Docker · NGINX · HTTPS/SSL · Git                 |
| Web Maintenance        | JavaScript · jQuery · Ajax · HTML · CSS · Bootstrap      |
| Monitoring             | Web/API Health Check · Service Status Check · Alert Flow |
| Data / Messaging       | MQTT · Data Processing · API Response Data Handling      |

---

# Security Notice

이 저장소에는 회사 내부 소스코드, 실제 API 명세, DB 구조 원문, 서버 정보, 계정 정보, 고객 정보, 운영 문서 원문을 포함하지 않습니다.

모든 내용은 실제 업무 경험을 기반으로 하되, 외부 공개 가능한 범위로 추상화하여 작성했습니다.

---

## Related Project

### university-cms-php

PHP·MySQL 기반 CMS 구조를 직접 설계하고 구현하기 위한 개인 프로젝트입니다.

실무에서 경험한 PHP 웹서비스 운영·유지보수 흐름을 바탕으로, 대학교·공공기관 부속 홈페이지 관리 시스템을 가정해 요구사항정의서와 DB 설계 초안을 작성했습니다.

Repository: https://github.com/kimsixsue/university-cms-php
