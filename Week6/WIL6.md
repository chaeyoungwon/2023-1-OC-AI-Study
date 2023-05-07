코드 사용, 그래프 결과는 jupyter 파일에 있습니다!!

<xgboost 사용>

linear regression을 사용했을 떄보다 r squared 값이 작고 MAE, MSE, RMSE 값은 크다. r squared가 1에 가까울 수록 좋은 성능을 갖고 있으며 나머지는 0에 가까울 수록 좋은 성능을 갖고 있기에 성능은 xgboost < linear regression이라고 볼 수 있다.

<lightgbm 사용>

linear regression을 사용했을 떄보다 r squared 값이 작고 MAE, MSE, RMSE 값은 크다. r squared가 1에 가까울 수록 좋은 성능을 갖고 있으며 나머지는 0에 가까울 수록 좋은 성능을 갖고 있기에 성능은 lightgbm < linear regression이라고 볼 수 있다.
그러나 xgboost보다는 r squared 값이 크고 MAE, MSE, RMSE 값은 작다.
성능은 lightgbm > xgboost 라고 볼 수 있다.