<xgboost 사용>

![xgb.image]("C:\Users\epopc\OneDrive\바탕 화면\인공지능 과제 다운\06_MLSupervised\xgb.png")

linear regression을 사용했을 떄보다 r squared 값이 작고 MAE, MSE, RMSE 값은 크다. r squared가 1에 가까울 수록 좋은 성능을 갖고 있으며 나머지는 0에 가까울 수록 좋은 성능을 갖고 있기에 성능은 xgboost < linear regression이라고 볼 수 있다.

<lightgbm 사용>

![lgb.image]("C:\Users\epopc\OneDrive\바탕 화면\인공지능 과제 다운\06_MLSupervised\lgb.png")

linear regression을 사용했을 떄보다 r squared 값이 작고 MAE, MSE, RMSE 값은 크다. r squared가 1에 가까울 수록 좋은 성능을 갖고 있으며 나머지는 0에 가까울 수록 좋은 성능을 갖고 있기에 성능은 lightgbm < linear regression이라고 볼 수 있다.
그러나 xgboost보다는 r squared 값이 크고 MAE, MSE, RMSE 값은 작다.
성능은 lightgbm > xgboost 라고 볼 수 있다.