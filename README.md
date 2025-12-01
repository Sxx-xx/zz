# 대학생 창작모빌리티 무인자율주행 부문

## 1. 프로젝트 개요 (Overview)
이 프로젝트는 자율주행 차량의 경로 추종 및 주차 알고리즘을 구현한 결과물입니다.
(예: Pure Pursuit 알고리즘과 Reed-Shepp 곡선을 활용하여 자동 주차 기능을 구현했습니다.)

## 2. 주요 기능 (Key Features)
* **GPS PATH TRACKING**
* **종방형 제어:** PID 알고리즘 기반 속도 제어
* **횡방향 제어:** Pure Pursuit 알고리즘을 통한 경로 추적
* **장애물 인식:** LiDAR 데이터를 기반으로 한 정적 장애물 회피, 비전 기반 주차공간 인지
* **C-ITS:** RSU<-->OBU를 통한 신호 확인

## 3. 대회 미션
* **주행:** GPS PATH TRAKING을 이용 (1m 보간), PID제어를 통한 속도 조정, PURE PURSUIT제어를 통한 스티어값 조절
* **라이다 이용 장애물 회피:**
* **camera line tarking:** 

## 4. 개발 환경 (Environment)
* **OS:** Ubuntu 20.04
* **Language:** Python 3.8, C++
* **Hardware:** erp-42
