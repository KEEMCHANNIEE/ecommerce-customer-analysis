# 🛒 E-commerce Customer Behavior Analysis

분류 모델을 활용해 고객의 구매 전환 가능성을 예측한 프로젝트입니다.  
Kaggle에서 제공하는 이커머스 행동 로그 데이터를 바탕으로, 실제 서비스 적용을 고려한 분석 및 모델링을 수행했습니다.

---

## 📌 프로젝트 개요

- **목표**: 고객 행동 데이터를 기반으로 구매 전환 여부 예측  
- **데이터**: Kaggle 공개 이커머스 로그 데이터  
- **모델링**: Logistic Regression, Random Forest, Gradient Boosting 등 다양한 분류 모델 성능 비교  

---

## 🧪 주요 분석 내용

- 고객 행동 EDA: 재방문율, 장바구니 이탈률 등 분석  
- 구매 여부(`purchase = 1`)를 타겟으로 한 **이진 분류 문제** 설정  
- Feature Engineering: 페이지 체류 시간, 사용자 유형 등  
- 성능 비교: Accuracy, ROC-AUC, F1-score 등 주요 지표 기준 평가  

---

## 🗂️ 파일 구성

| 파일 경로 | 설명 |
|-----------|------|
| `notebooks/ecommerce_analysis_modeling.ipynb` | 전체 분석 및 모델링 파이프라인 |
| `notebooks/ecommerce(3).ipynb` | EDA 및 주요 인사이트 도출 |
| `data/final_dataset.xlsx` | 전처리된 최종 데이터셋 (업로드 시 주의) |

---

## 🛠 사용 기술

- **언어 및 라이브러리**: Python (pandas, scikit-learn, matplotlib, seaborn)  
- **분석 환경**: Jupyter Notebook  
- **데이터 출처**: [Kaggle - E-commerce Behavior Data](https://www.kaggle.com/datasets/thedevastator/ecommerce-behavior-data-from-multi-category-store)

---

## 📈 프로젝트 결과 (요약)

- Random Forest 모델 기준 ROC-AUC **0.87** 이상 달성  
- 사용자 유형별 맞춤 전략 수립 가능성 도출  
- 실제 이커머스 마케팅/전환 분석에 적용 가능한 인사이트 확보  

---

