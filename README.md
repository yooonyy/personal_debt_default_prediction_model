# 채무불이행 분류 예측 모델

## 프로젝트 개요
이 프로젝트는 train 데이터를 분석하고, 다양한 전처리 방법과 모델을 적용하여 채무불이행 사례를 분류하는 예측 모델을 구축합니다. 심층신경망(Deep Neural Network, DNN), 결정트리(Decision Tree), 로지스틱회귀(Logistic Regression) 등의 기법을 사용하여 데이터에서 통찰을 얻고, 더 나은 예측 성능을 달성하기 위한 모델링 접근법을 탐색합니다.

## 데이터 탐색 및 전처리
- Pandas를 사용하여 데이터셋을 로드하고 탐색합니다.
- 중복 데이터 제거, 결측치 처리, 이상치 탐지 및 처리를 수행합니다.
- 일부 데이터 불균형 문제를 해결하기 위해 SMOTE 기법을 적용합니다.
- 수치형 변수를 표준화하고 범주형 변수를 가변수화합니다.

## 모델 소개
- DNN: 복잡한 비선형 관계를 모델링할 수 있는 심층신경망을 구축합니다.
- 결정트리: 데이터의 의사결정 규칙을 트리 구조로 시각화합니다.
- 로지스틱회귀: 사건의 발생 가능성을 예측합니다.
- 클러스터분석 및 SOM: 데이터를 클러스터로 분류하고 대표점을 찾습니다.

## 모델 학습 및 최종 예측
- 각 모델에 대한 학습 과정을 수행하고, 하이퍼파라미터 튜닝을 통해 최적의 모델을 선택합니다.
- 교차 검증 및 기타 모델 검증 기법을 사용하여 모델의 일반화 성능을 평가합니다.
- 최종적으로 선정된 모델을 사용하여 새로운 데이터셋의 채무불이행 여부를 예측합니다.

[보고서 PDF 파일](https://github.com/yooonyy/personal_debt_default_prediction_model/blob/main/report.pdf)
