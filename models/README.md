# Models Directory


- 머신러닝 모델 및 딥러닝 모델을 저장합니다.
- 앙상블 및 스태킹 기법과 다른 모델을 비교할 수 있습니다.

## model
- RandomForest
- XGBoost
- LightGBM
- LSTM


## 평가지표
RMSE(Root Mean Squared Error)

<img src="https://github.com/yeardream2-KurlyProject/products_price_predict/blob/main/models/rmse.png" width="200" style="float:left" />

RMSE의 경우 MSE는 제곱을 하기 때문에 MAE와는 다르게 모델의 예측값과 실제값 차이의 면적의 합이다. 이런 차이로 특이값이 존재하면 **수치가 많이 늘어나며 특이치에 민감하다**는 단점을 보완한 RMSE를 사용하면 **오류 지표를 실제 값과 유사한 단위**로 다시 변환하여 해석에 용이함.
