# Project_baechu

# <국내 배추 가격 추이 예측>

* 데이터 : Dacon, Investing.com, 기상자료개방포탈, 리얼미터
* 데이터기간 : 2018년~2021년
* 분석대상(Y) : 총 16개 품종 배추 월별 평균가 예측
* 활용변수(X) : 환율, Korea_CPI, 지점별 기상 데이터, 대통령 지지율, 총반입량(kg), 중간가, 최저가, 최고가, 경매건수, 전순 평균가격, 전달 평균가격, 전년 평균가격, 평년 평균가격, 계절 변수, 날짜 변수 등

---
* 활용 알고리즘 후보 :
    * Machine Learning 5종: Logistic Regression, Random Forest, XGBoost, LGBM, CatBoost
    * Deep Learning 2종: Multi-Layer Perception (MLP), Convolutional Neural Network (CNN)
 
      ![화면 캡처 2024-12-05 045041](https://github.com/user-attachments/assets/3a472bf7-3dd3-43d8-98f1-34703872d828)

---
* XAI (Explainable AI) 분석:
   * SHAP (SHapley Additive exPlanations)**을 활용하여 모델의 예측 결과를 해석
   * SHAP 값을 통해 각 변수의 기여도를 분석하고, 기부 여부 예측에 가장 큰 영향을 미치는 주요 변수를 식별
---
(상위 8개 변수 제외)


![화면 캡처 2024-12-05 050057](https://github.com/user-attachments/assets/2bcd88be-a64e-4850-ba18-f525b8d55de5)


