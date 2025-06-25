🛒 E-commerce Customer Behavior Analysis (Kaggle Dataset 기반)
고객의 구매 행동 데이터를 분석하여 주요 패턴을 파악하고, 분류 모델을 통해 구매 예측을 수행한 프로젝트입니다.
Kaggle에서 제공하는 이커머스 행동 로그 데이터를 활용하였으며, 실제 비즈니스 적용 가능성을 염두에 두고 분석하였습니다.

📌 프로젝트 개요
목표: 고객 행동 데이터 기반으로 구매 전환 가능성 예측
데이터: Kaggle 공개 이커머스 로그 데이터 사용 (클릭, 장바구니, 구매 이력 등)
모델: Logistic Regression, Random Forest, Gradient Boosting 등 다양한 분류 모델 비교
🧪 주요 분석 내용
EDA를 통한 고객 행동 특성 파악 (재방문율, 장바구니 이탈 등)
구매 전환(y=1) 여부를 타겟으로 한 이진 분류
다양한 feature engineering 시도 (페이지 머문 시간, 사용자 유형 등)
성능 비교 (Accuracy, ROC-AUC, F1-score 중심)
🗂️ 파일 구성
파일명	설명
notebooks/ecommerce_analysis_modeling.ipynb	전체 분석 및 모델링 파이프라인
notebooks/ecommerce(3).ipynb	EDA 및 주요 인사이트 도출
data/final_dataset.xlsx	전처리된 최종 데이터셋 (업로드 시 주의)
🛠 사용 기술
Python (pandas, scikit-learn, matplotlib, seaborn)
Jupyter Notebook
Kaggle Dataset 활용
