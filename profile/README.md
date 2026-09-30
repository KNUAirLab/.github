# KNUAirLab
> 기상·대기환경 데이터를 활용한 미세먼지 예측 및 시각화 시스템을 개발합니다.

## About
KNUAirLab은 기상·대기환경 데이터와 과거 PM10·PM2.5 측정값을 활용하여
미래 미세먼지 농도를 예측하고, 결과를 지도와 그래프로 제공하는 프로젝트입니다.

사용자 위치를 기반으로 인근 측정소의 현재 대기질과 향후 예측 정보를 제공하며,
LLM과 RAG를 활용한 AI 요약 및 추천 Q&A를 통해 대기질 정보를 쉽게 설명하는 것을 목표로 합니다.

현재는 데이터 수집·전처리와 기상 요소 및 미세먼지 농도 간의 관계 분석을 중심으로
예측 모델과 웹 기반 시스템을 개발할 계획입니다.

## Features
- 기상·대기환경 데이터 수집 및 전처리
- 기상 요소와 미세먼지 농도 간의 관계 분석
- 머신러닝·딥러닝 기반 PM10·PM2.5 농도 예측
- GPS 기반 인근 측정소 조회
- 현재 관측값과 예측 결과의 지도·그래프 시각화
- RAG 기반 AI 요약 및 추천 Q&A

## Tech Stack

### Language & Framework
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

### AI / ML
![OpenAI](https://img.shields.io/badge/OpenAI-000000?style=for-the-badge&logo=openai&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-0A66C2?style=for-the-badge&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6366F1?style=for-the-badge&logoColor=white)

### Data Processing
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### Tools
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## Data Sources
- 에어코리아: 측정소 정보 및 PM10·PM2.5 등 대기오염 관측 데이터
- 기상청: 기온·습도·풍속·풍향·강수량 등 기상 데이터
- 공공기관 자료: 미세먼지 설명 및 행동요령 등 RAG 참고 자료
