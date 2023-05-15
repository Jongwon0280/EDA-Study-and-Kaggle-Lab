# 캐글데이터를 활용한 EDA 및 ML모델링

<br>

Kaggle의 데이터셋을 활용하여 다음과 같이 진행하였습니다.

<br>

> 1.정형데이터 분석 및 인사이트 도출


> 2.정형데이터 타겟 예측(분류, 회귀)
  
> 3.비정형데이터 분석 및 모델링

<br>

### 분석 및 시각화

<br>

분석은 상관계수, 데이터분포(왜도, 첨도), 이상치 분석등을 진행하였으며, 

시각화는 seaborn, matplotlib을 활용하여 특성에 적합한 시각화를 하였으며, 전처리 및 feature selection하는데 사용하였습니다.

<br>

### 모델링

<br>

정형데이터 : ML Tree based Ensemble

> 정형데이터는 ML기반으로 접근하였으며, 모델향상을 위해 자동하이퍼파라미터 Optuna나 sklearn.gridsearch를 활용하였습니다.



비정형데이터 : FNN, CNN

> 비정형데이터는 딥러닝으로 접근하였으며, 모델향상을 위해 batch, epochs, early stopping option, learning rate 옵션을 활용하였습니다.

<br>


### 데이터출처
> **1. 인사이트 도출**


>LoanData : https://www.kaggle.com/itsmesunil/bank-loan-modelling

>SalesData : https://www.kaggle.com/rohitsahoo/sales-forecasting

>StarwarsData : https://dplyr.tidyverse.org/reference/starwars.html

<br>

> **2. (비)정형데이터 모델링 및 성능향상**



>MushroomData : https://www.kaggle.com/datasets/uciml/mushroom-classification

>Autism Data : https://www.kaggle.com/competitions/autismdiagnosis/overview

>Skin Cancer Data : https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000

>Titanic Data : https://www.kaggle.com/datasets/heptapod/titanic
