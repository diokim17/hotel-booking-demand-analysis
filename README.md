# 🏨 Hotel Booking Demand Analysis

Hotel Booking Demand Dataset을 활용하여 호텔 예약 취소에 영향을 미치는 요인을 분석하고,
예약 취소율을 낮출 수 있는 개선 방안을 도출한 데이터 분석 프로젝트입니다.

> Codeit AI Engineer Sprint Mission

---

## 프로젝트 개요

예약 취소는 호텔의 객실 운영과 매출에 직접적인 영향을 미치는 중요한 요소입니다.

본 프로젝트에서는 예약 취소 여부와 관련된 다양한 변수를 분석하여

- 예약 취소와 관련된 주요 요인 파악
- 데이터 기반 가설 수립 및 검증
- 예약 취소율 개선 아이디어 도출

을 목표로 분석을 진행하였습니다.

---

## Dataset

- [Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- 기간 : 2026.06.10 ~ 2026.06.15
- Hotel Type
  - Resort Hotel
  - City Hotel

(실제 작성된 코드의 경우 코드잇에서 제공한 데이터로 일부 수정을 가한 데이터입니다.
따라서 캐글에서 제공하는 데이터와 100% 동일하지는 않습니다.)
---

## 분석 과정

1. 데이터 탐색(EDA)
2. 결측치 및 데이터 확인
3. 가설 수립
4. 가설 검증
5. 인사이트 도출
6. 예약 취소율 개선 방안 제안

---

## 분석 가설

- 과거 예약 취소 경험이 있는 고객은 예약을 더 많이 취소할 것이다.
- 예약 대기 기간이 길수록 예약 취소율이 높을 것이다.
- 주차 공간을 요청한 고객은 예약 취소율이 낮을 것이다.
- 어린이 또는 영유아를 동반한 고객은 예약 취소율이 높을 것이다.

---

## 프로젝트 구조

```
hotel-booking-demand-analysis
│
├── data
│   └── hotel_data_modified.csv
│
├── hotel-booking-demand-analysis.ipynb
│
└── README.md
```

---

## 개발 환경

| 항목 | 내용 |
|------|------|
| Language | Python 3 |
| Library | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Environment | Google Colab |

---

## 주요 분석 결과

- 과거 예약 취소 경험은 예약 취소와 매우 높은 관련성을 보였다.
- 예약 대기 기간이 길수록 취소율이 증가하였다.
- 주차 공간 요청 고객은 취소율이 매우 낮았다.
- 자녀 동반 여부는 취소율과 큰 관련성이 없었다.

---

## Blog

프로젝트 분석 과정은 아래 글에서 자세히 확인할 수 있습니다.

- Velog : [(Hotel Booking Demand 데이터 분석 - 예약 취소율의 원인 찾기)](https://velog.io/@diokim17/%EC%BD%94%EB%93%9C%EC%9E%87-%EC%8A%A4%ED%94%84%EB%A6%B0%ED%8A%B8%EB%AF%B8%EC%85%98Hotel-Booking-Demand-%EB%8D%B0%EC%9D%B4%ED%84%B0-%EB%B6%84%EC%84%9D-%EC%98%88%EC%95%BD-%EC%B7%A8%EC%86%8C%EC%9C%A8%EC%9D%98-%EC%9B%90%EC%9D%B8-%EC%B0%BE%EA%B8%B0)

---

## License

Educational Purpose
