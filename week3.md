핀테크 서비스 개발을 위한 AI 프로젝트 부트업 과정

Week3

# 4.  비즈니스 케이스 스터디

## - 트리와 앙상블:

1. [트리-결정트리](notebooks/4-13결정트리.ipynb)
2. [트리-교차검증](notebooks/4-14교차검증_그리드서치.ipynb)
3. [트리-앙상블](notebooks/4-15앙상블.ipynb)



## - 학습 평가
 - `교안2-30평가와성능(202209).pdf`  (공유폴더)
 -  [학습 평가지표](notebooks/4-18모델평가지표.ipynb)



<br>

# 5. 비지도학습

1. 비지도학습 : `교안2-40비지도학습(202208).pdf` (공유폴더)
2. [비지도-주성분분석](notebooks/4-21비지도-주성분분석(cancer).ipynb)
3. [비지도-KMeans 군집](notebooks/4-25비지도-군집(KMeans).ipynb)
4. [비지도-이상탐지(급여 데이터 이상탐지)](notebooks/4-27비지도-이상탐지.ipynb)

<br>

# 6. 비즈니스 케이스 스터디 : 딥러닝

딥러닝 이용 고액 이탈 예측을 위한 분류모형 및 로지스틱

## - 딥러닝 소개

1. 딥러닝 텐서플로우 시작

   - 머신러닝에서 딥러닝: `교안tf2-00ML에서DL.pdf` (공유폴더)
       - 참고: https://velog.io/@nawnoes/01.-DQNDeep-Q-Leaning
   - 실행환경
       - 개인 PC에서 CPU환경에서 수행
           - 참고: `교안tf2-텐서플로우GPU설치(윈도우즈)` (공유폴더)
       - 구글 코랩에서 수행: [google_colab.ipynb](notebooks/google_colab_matplotlib(202209).ipynb)
       - [TensorFlow 준비](notebooks/5-02TensorFlow준비.ipynb)

2. Keras / Tensorflow 딥러닝
    - 텐서플로우와 케라스: `교안tf2-02Tensorflow와_Keras1.pdf` (공유폴더)
    - [TensorFlow와 Keras1 소개](notebooks/5-10Tensorflow_Keras1.ipynb)
    - [TensorFlow와 Keras2인공신경망](notebooks/5-10Tensorflow_Keras2_인공신경망.ipynb)
    - [TensorFlow와 Keras3심층신경망](notebooks/5-10Tensorflow_Keras3_심층신경망.ipynb)


3. `교안tf2-03-회귀분석(202209).pdf` (공유폴더)
   1. [TF 딥러닝-회귀.ipynb](notebooks/5-11TF2-회귀.ipynb)
   1. [TF 딥러닝-회귀ex_mpg](notebooks/5-11회귀ex-mpg.ipynb)
---


## "과제"


1. 실습 노트북을 활용해 LinearRegressor, SVM, KNN Regressor 등을 이용해 다시 학습해 보세요.
   - [고객연간지출액(회귀)](notebooks/분석-고객연간지출액(회귀).ipynb)
       - Ecommerce Customers.csv
   - [KNN 회귀](notebooks/4-10지도-회귀ex1-KNN-0.ipynb)
2. "실습" XGBoost/LightGBM을 gridsearchcv 이용해 파라메터 찾아 보세요!!!
3. "실습" 암 데이터를 XGBoost/LightGBM 와 gridsearchcv 이용 학습해 보세요.
<!-- 사용한 `데이터분석-주가데이터(2021시가총액)`을 FinanceDataReader 를 활용해 2022년 자료를 사용해 분석해 보자. -->
4. 실습 [비지도-이상탐지(급여 데이터 이상탐지)](notebooks/4-27비지도-이상탐지.ipynb)
