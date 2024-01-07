# Kaggle Competition 정리

[1. Spaceship Titanic](#1-spaceship-titanic)



## 1. Spaceship Titanic
- kaggle url: https://www.kaggle.com/competitions/spaceship-titanic

- source flow (work flow)
    1. [fst_try.ipynb](spaceship_titanic/fst_try.ipynb): 첫번째 시도 <br>
        tensorflow 이용하여 Dense Layer 여러층 쌓아놓은 구조

    2. [sec_try.ipynb](spaceship_titanic/sec_try.ipynb): 두번째 시도 <br>
        scikit-learn 모듈의 LogisticRegression 함수를 이용해 로지스틱-회귀 모델 사용

    3. [third_try.ipynb](spaceship_titanic/third_try.ipynb): 세번쨰 시도 <br>
        Tensorflow 모듈을 사용한 의사결정트리 사용

    4. [fourth_try.ipynb](spaceship_titanic/fourth_try.ipynb): 네번째 시도 <br>
        Tfdf(Tensorflow Decison Forest) decision_forest에서 지원하는 모델 모두 써보기

    5. 위의 시도들 모두 정확성이 많이 낮음\
        -> 데이터 전처리가 잘 되지 않은 것으로 판단됨.\
        -> 데이터 전처리에 집중.

    6. [preprocess.ipynb](spaceship_titanic/preprocess.ipynb): 데이터 전처리 <br>
        데이터 전처리에 집중