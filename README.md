<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Lim%20Gyeongpyo&fontSize=48&fontColor=ffffff&fontAlignY=36&desc=Embedded%20Systems%20%C2%B7%20Control%20%C2%B7%20Data&descSize=16&descAlignY=56&animation=fadeIn" alt="임경표 | Embedded Systems · Control · Data" />
</p>

<p align="center">
  <a href="https://github.com/lvgang99"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="#featured-projects"><img src="https://img.shields.io/badge/Projects-2C5364?style=for-the-badge" alt="Projects" /></a>
  <a href="#awards"><img src="https://img.shields.io/badge/Awards-203A43?style=for-the-badge" alt="Awards" /></a>
</p>

<h3 align="center">하드웨어의 특성을 바탕으로 제어 기능을 구현하고, 실제 동작과 데이터로 검증합니다.</h3>

---

## Summary

| 분야 | 역량 | 근거 |
|---|---|---|
| **Embedded&nbsp;Control** | MCU 기반 구동 제어와 센서 보정, 예외 상황의 복구 기능 구현 | 수색 로봇의 모터 제어·헤드트래킹 개발<br/>상보필터 적용 및 사용자 입력에 따른 기준각 재설정 |
| **System&nbsp;Integration** | 센서 입력부터 통신, 제어 판단, 구동 출력까지 연결 | Arduino–STM32 무선 제어<br/>Ethernet TCP/IP·UART 기반 스마트홈 통합 |
| **Test&nbsp;·&nbsp;Validation** | 시험 조건 설계와 CAN 데이터 분석을 통한 동작 검증 | 전기차 성능 인증시험<br/>주행 시나리오 설계·이슈 분석·TDP 작성 |
| **Data&nbsp;·&nbsp;AI** | 제조 데이터의 특성을 분석하고 전처리와 모델 비교로 예측 성능 개선 | 제품 품질 예측 프로젝트<br/>Gradient Boost 모델 선정·MAPE 0.5~0.9% |

---

## Experience

| 기간 | 소속 | 내용 |
|:---:|---|---|
| 2025.07&nbsp;–&nbsp;2025.11 | **오토노머스에이투지**<br/>차량시험팀 · 매니저 | 전기차 성능 검증을 위해 인증 기준에 맞는 시험 조건과 주행 시나리오 설계<br/>CANoe로 차속·전력 소비·SOC 등 차량 데이터를 수집하고, 이상 발생 시 운행 조건과 신호 흐름을 분석해 원인 추적<br/>**문서화** 육안 검수·기본 작동·성능 평가를 위한 TDP(Test Development Process) 작성 |

---

## Featured Projects

| 프로젝트 | 내용 |
|---|---|
| **가변바퀴와 영상처리를 이용한<br/>붕괴 현장 수색 소형 로봇**<br/>졸업작품 | 협소한 공간과 험지에서 이동하고, 사용자 머리 움직임에 맞춰 카메라 시점을 바꾸는 수색 로봇<br/>**담당** 팀장으로서 시스템 설계, MCU 기반 모터 제어, 무선 통신, 헤드트래킹 개발<br/>**구현** 조이스틱 입력을 RF 통신으로 전달하고 STM32에서 주행·바퀴 변형 제어. MPU6050에 상보필터를 적용하고, 충격으로 기준 방향이 어긋나면 사용자 입력으로 기준각을 재설정하도록 구현<br/>**결과** 110mm 장애물 극복 및 험지 주행 확인. 모터 구동·바퀴 변형·헤드트래킹·영상 전송의 통합 동작 확인<br/>**Stack** C, STM32, Arduino, nRF24L01, SPI, PWM, MPU6050 |
| **Smart Home**<br/>제어용 통신 프로젝트 | 온습도·우천 상태에 따른 자동 제어와 Android 명령을 통한 원격 제어를 결합한 스마트홈<br/>**구현** Arduino의 센서 데이터를 UART로 STM32에 전달하고, PC·Android와 Ethernet TCP/IP로 연결. 센서 데이터와 사용자 명령을 구분해 히터·에어컨·창문 동작에 반영<br/>**결과** 센서 입력부터 통신, 제어 판단, 구동 출력까지 STM32를 중심으로 통합<br/>**Stack** C, STM32, Arduino, Ethernet TCP/IP, UART |
| **제조 데이터 기반 품질 예측**<br/>K-Digital 프로젝트 | 생산 데이터로 제품 품질을 예측하기 위한 전처리 및 머신러닝 모델 비교<br/>**분석** 2,875개 변수 중 전체가 결측인 82개 변수를 제거하고, 결측 비율과 변수 분포를 바탕으로 데이터 정제. 학습·평가 데이터 비율 실험과 K-Fold 검증으로 모델별 성능 비교<br/>**결과** Gradient Boost 모델을 최종 선정하고 MAPE 0.5~0.9% 수준의 예측 오차 확인<br/>**Stack** Python, 데이터 전처리, Gradient Boost, K-Fold |

---

## Activities

| 기간 | 활동 | 내용 |
|:---:|---|---|
| 2023&nbsp;–&nbsp;2024 | **MCC 학술동아리 회장** | 임원진의 역할을 나누고 협업 체계를 정비해 학술 활동과 학부 행사의 기획·진행 총괄<br/>임베디드·로봇·제어 분야의 전공 교육과 대회 운영을 이끌며 구성원이 맡은 역할을 실행할 수 있도록 조율 |
| 2023 | **제4회 총장배 로봇 프로그래밍 경진대회**<br/>햄스터로봇 C언어 부문 총괄 | 센서 입력을 활용하는 제어 문제를 직접 출제하고 정답 코드 작성<br/>참가자 수준을 고려해 센서 데이터 해석·제어 흐름·디버깅 교육을 구성하고, 단계별 문제 난이도와 평가 기준 설계<br/>**Stack** C, Visual Studio, 햄스터 로봇 |

---

## Awards

| 연도 | 결과 | 대회 |
|:---:|:---:|---|
| 2024 | **학부생 논문상** | ICROS 2024 제39회 제어로봇시스템학회 학술대회 학부생 논문경진대회<br/>가변바퀴와 영상처리를 이용한 수색 로봇 연구 |
| 2022 | **1등 · 총장상** | 제3회 총장배 로봇 프로그래밍 경진대회<br/>드론로봇 C언어 부문 |

---

## Tech Stack

| 분야 | 기술 및 활용 |
|---|---|
| **Language** | C — MCU 제어·로봇 프로그래밍<br/>Python — 제조 데이터 분석·머신러닝<br/>C++ — 기초 문법·알고리즘 학습 |
| **Embedded&nbsp;·&nbsp;Control** | STM32, Arduino, PWM, 센서 기반 제어, Complementary Filter |
| **Communication** | SPI, UART, Ethernet TCP/IP, nRF24L01 기반 RF 통신 |
| **Test&nbsp;·&nbsp;Measurement** | CANoe, CAN 데이터 분석, 오실로스코프, 파워서플라이, OBD, CAN 인터페이스 |
| **Data&nbsp;·&nbsp;ML** | 데이터 전처리, 변수 분석, Gradient Boost, K-Fold 검증 |

---

## Education

| 기간 | 과정 | 비고 |
|:---:|---|---|
| 2026.07&nbsp;–&nbsp;현재 | **SSAFY 16기** | 소프트웨어·AI 교육 |
| 2019&nbsp;–&nbsp;2025 | **한국공학대학교** | 메카트로닉스공학 전공<br/>스마트팩토리 복수전공 · 학사 졸업 |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,100:0F2027&height=100&section=footer" alt="" />
</p>
