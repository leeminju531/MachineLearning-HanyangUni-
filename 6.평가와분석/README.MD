## Logistic Regression 학습 모델에 대해, 적합한 분류모델을 추출하는데 있어 알아본다.

1. kfold 를 통해, 훈련될 데이터셋이 편향되지 않은 결과를 갖도록 확인해본다.

2. Recall , Precision , Fall-out, Accuracy의 평가 지표를 확인한다.


![image](https://user-images.githubusercontent.com/70446214/97321536-5557e100-18b2-11eb-89b4-8e92cfe350a1.png)

![image](https://user-images.githubusercontent.com/70446214/97321559-5be65880-18b2-11eb-96d0-e46a90e493d5.png)

![image](https://user-images.githubusercontent.com/70446214/97321591-630d6680-18b2-11eb-894f-da663d8dc27a.png)

![image](https://user-images.githubusercontent.com/70446214/97321607-69034780-18b2-11eb-9e6b-3212ac61411a.png)



F1SCORE 표를 그려, Threshold 값에 따른 RECALL,PRECISION.... 값들의 지표를 그려 결정한다.
(F1-Score는 recall과 precision이 둘다 균일하게 높은 값을 가질 수 있는 값이다.)
![image](https://user-images.githubusercontent.com/70446214/97321648-74567300-18b2-11eb-8c38-49b5f12f1b14.png)


*암환자 판별의 경우, 양성인 데이터를 음성으로 판단하면 안된다 ->recall이 중요하다.


*스팸메일의 경우, 음성인 데이터를 양성으로 판단하면 안된다 -> precision이 중요요소


3. ROC 그래프를 그려본다.


![image](https://user-images.githubusercontent.com/70446214/97322690-63f2c800-18b3-11eb-8dca-ea01e46ac230.png)
