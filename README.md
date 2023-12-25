![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=데돌이_데이터분석&fontSize=40)

------------

## 데돌이

### 🔧 사용한 Tool
<div style="display: flex; justify-content: center;">
  <img src="https://img.shields.io/badge/Python-3776AB?&style=flat&logo=python&logoColor=white" style="margin-right: 10px;">
  <img src="https://img.shields.io/badge/Anaconda-44A833?&style=flat&logo=anaconda&logoColor=white" style="margin-right: 10px;">
  <img src="https://img.shields.io/badge/pandas-150458?&style=flat&logo=pandas&logoColor=white" style="margin-right: 10px;">
  <img src="https://img.shields.io/badge/scikitlearn-F7931E?&style=flat&logo=scikitlearn&logoColor=white" style="margin-right: 10px;">
</div>

------------

### 📊 데이터 분석 과정

#### 🌲트리 모델의 경우

1. 분석할 데이터 파일 불러오기
2. 훈련 데이터와 테스트 데이터 분리하기
3. 사전 가지치기 (과대 적합 방지)
4. 학습률 낮추기 (과한 트리 보정 방지)
5. 모델 생성하기
6. 정확도 및 변수 중요도 확인하기


#### 📈 회귀 모델의 경우
1. 분석할 데이터 파일 불러오기
2. 훈련 데이터와 테스트 데이터 분리하기
3. 스케일링
4. 모델 생성하기
5. 정확도 및 변수 중요도 확인하기

------------

### 🖥️ 데이터 분석 모델

#### 1. 로지스틱 회귀 (Logistic Regression)

- 회귀 분석을 사용해 종속 변수가 이진(binary)인 경우 주로 사용되는 통계적 모델로, 선형 회귀를 기반으로 하지만 종속 변수가 범주형에 속하므로 일반적 선형 회귀 모델을 적용할 수 없는 경우에 유용

- 종속 변수가 특정 클래스에 속할 확률을 예측하는 데 사용하며 예측된 확률은 0과 1사이의 값으로 제한되고, 일반적으로 0.5를 기준으로 0.5보다 크면 한 클래스에, 0.5보다 작으면 다른 클래스에 할당

#### 2. 그래디언트 부스팅 트리 (Gradient Boosting Tree)

- 앙상블 학습 방법 중 하나로, 결정 트리를 기반으로 하는 예측 모델이며 약한 학습자(weak learner)들을 결합해 강력한 학습자(strong learner)를 구성하는 방식으로 동작

#### 3. 랜덤 포레스트 앙상블 (Random Forest)

- 앙상블 학습 방법 중 하나로, 여러 결정 트리를 조합해 높은 성능의 예측 모델을 생성하는 모델로, 결정 트리의 과적합 문제를 완화하고, 데이터의 일반적인 패턴을 더 잘 학습할 수 있도록 설계됨

------------

### 👍 성능

#### 정확도

- 0과 1 사이의 값으로 설정되며, 1에 가까울수록 높은 정확도

#### ROC Curve

- 이진 분류 모델의 성능을 시각적으로 평기하는 데 사용되는 도구
- 좋은 모델일 수록 왼쪽 상단에 가깝게 위치

------------

![Footer](https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=footer)
