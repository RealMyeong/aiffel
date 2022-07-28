# Aiffel DataThon

데이터톤 팀 통합본은 슈슈슈슉.ipynb 입니다.

## 1. 팀명 & 조원

팀명 : 🗿슈슉, 슈슉, 슈퍼마켓

조장 : 이재은

팀원 : 권세영, 김동욱, 진명

## 2. 기간

2022.07.26 ~ 2022.07.29

## 3. 데이터소개

  - 슈퍼마켓의 매출과 매장의 크기, 일일 이용자수의 관계를 분석한 데이터이다.
  
    | 이름 | 설명 | 변수형
    |:---:|:---:|:---:|
    |Store ID|(index) 매장 번호|int|
    |Store Area|매장 크기| int|
    |Items_Available| 판매가능한 품목 수| int|  
    |Daily_Customer_Count| 일일 평균 방문자 수|int|
    |Store_Sales| 매출|int|

## 4. 진행 방향

  - EDA
    - Summary : head, tail, shape, info, 데이터 소개 및 feature 설명
    - Statistics : vif, 왜도, 첨도
    
  - FE
    - 이상치 처리
      - 시각적 : box-plot
      - 통계적 : IQR, z-score
    - 중복치 확인
    - 범주화
    - 정규화
    
    
## 5. 회고
