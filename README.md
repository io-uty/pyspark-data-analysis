# PySpark Data Analysis

Google Colab 환경에서 PySpark를 활용한 대용량 데이터 분석 프로젝트입니다.

## 분석 목록

### 영화 평점 분석 (MovieLens)
`movie_rating_analysis.ipynb`
- 20~30대 여성 사용자 그룹 필터링 후 장르별 평균 평점 산출
- War · Romance · Musical 순으로 선호도 높음 확인
- 사용자별 리뷰 횟수 · 평균 평점 집계, 장르와 연령대 상관관계 분석

### 영화 장르 분석 (MovieLens)
`movie_genre_analysis.ipynb`
- ratings.csv · movie_genres.csv 조인 후 장르별 평점 분포 분석
- 중복 데이터 제거 및 장르별 정렬

### 서울 기상 데이터 분석
`weatherDB.ipynb`
- 2023년 4~9월 기상청 공공데이터 활용
- 폭염특보 횟수와 평균기온 관계 분석
- 자외선 지수 단계 수치화, 행정구역별 폭염 집중 지역 도출

### 식품 영양성분 분석
`food_nutrition_analysis.ipynb`
- 식품 DB 기반 칼로리 · 단백질 · 지방 · 탄수화물 데이터 정제
- 컬럼명 영문화 및 CSV 저장

## 기술 스택
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)

## 실행 환경
- Google Colab
- Apache Spark 3.5.1
- Java 8
