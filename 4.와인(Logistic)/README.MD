# leeminju531-IC_PBL-MachineLearning_wineclassification-LogisticRegression

1. pandas를 이용해 동일 column을 가진 csv 계열 데이터를 합친다.( 두 데이터간 구분을 위해, 새로운 데이터를 추가하고
'color' 열을 생성하여 redwine = 0 / whitewine = 1 로 구분한다

2. Logistic Regression을 이용하여 합쳐진 데이터프레임으로부터 redwine과 whitewine을 구분할 수 있는지 확인한다.

3. feature데이터를 분석해보면, 평균 편차 등의 특성이 다름 -> Normalization을 통해 feature 데이터를 전처리하고
학습을 통해 2의 결과와 비교해본다.

4. regression은 잘 분류하지만, 사람이 feature데이터간 어느 데이터가 중요한지 파악하기 힘들다.
Tree 계열의 머신러닝을 이용하면, feature 데이터의 중요도를 눈으로 확인할 수 있다(성능은 다소 떨어질수있다)
