# [유가 데이터 활용 주유소 분석](https://github.com/Raziel-JKM/Kaggle/blob/main/%EC%9C%A0%EA%B0%80%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%ED%99%9C%EC%9A%A9%20%EC%A3%BC%EC%9C%A0%EC%86%8C%20%EB%B6%84%EC%84%9D/%EC%9C%A0%EA%B0%80_%EB%8D%B0%EC%9D%B4%ED%84%B0_%EB%B6%84%EC%84%9D.ipynb)

# 프로젝트 목차

## 데이터 Cleansing 및 Feature Engineering: 분석을 위한 사전 점검 및 데이터 개괄 이해

1.1. 2018년 데이터 기준 데이터 Cleansing 및 Feature Engineering

1.2. Cleansing 및 Feature Engineering 함수 생성 및 전체 년도 데이터 적용

1.3. 연도별 데이터 Outer Join


## 주유소 개폐업 현황 분석: 연도별 주유소 ID 비교를 통한 개폐업 현황 분석

2.1. 연도별 개폐업 수치 분석


## 브랜드 분석: 브랜드별 가격경쟁력 및 시장점유율 분석

3.1. 주요 브랜드별 가격 Line Plot 분석

3.2. 주요 브랜드별 지난 4년간 시장 점유율 Stacked Bar Plot 및 Heatmap 분석


## 가격 분석: 주유소 및 지역 별 가격 편차 분석

4.1. 가격 분포 Boxplot

4.2. 지역별 가격 분포 Boxplot (Multiple Columns)

데이터 출처:

https://www.data.go.kr/data/15044628/fileData.do

Opinet 유가내려받기: 2018 ~ 2021년 4개년에 대해 각각 6월 1일~7일 데이터 추출

프로젝트에 필요한 컬럼만 추출

정유업체 전략기획팀 실무자의 입장에서 분석하여 주유소 시장에 대한 인사이트를 도출

주유소별로 7일치씩 쌓여있는 데이터를 요약하여 주유소별로 1개의 행이 되도록 각 년도 데이터를 가공

그리고 이 데이터를 통해 지난 4년동안 몇개의 주유소가 개업 및 폐업 했는지 분석

다음, 브랜드별 가격경쟁력 및 지난 4년간 시장 점유율 변화를 분석

마지막으로 주유소별 가격 편차가 어느정도 되는지 알아보고, 지역별로도 유의미한 차이가 있는지 분석
