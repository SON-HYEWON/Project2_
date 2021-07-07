# 🍷 Wine Planning with ML
기존에 존재하는 와인데이터를 바탕으로 해서, 새롭게 들어올 와인에 대한 점수를 예측하는 모델을 제작하였습니다.

## 1. Dataset
[해당 링크](https://www.kaggle.com/rajyellow46/wine-quality)의 데이터 셋을 이용했습니다.  
이 데이터 셋의 features는 다음과 같이 분류되어 있습니다.
1. **fixed acidity**  결합산 : 와인의 산도를 제어
2. **volatile acidity**  휘발산 : 와인의 향에 연관
3.   **citric acid**  구연산 :  와인의 신선함을 올려주는 역할, 산성화에 연관을 미침
4.  **residual sugar**  잔여 설탕 : 와인에 단맛을 올려줌
5. **chlorides**  염화물 : 와인의 신맛을 담당
6.  **free sulfur dioxide**  유리 화항
7.  **total sulfur dioxide**  총 이산화항 : 와인을 오래 보관하는 역할
8.  **density**  밀도 : 바디의 높고 낮음을 표현하는 와인의 무게감을 의미
9.  **pH**  산성도 : 와인의 신맛의 정도를 나타냄
10. **sulphates**  황산염
11.  **alcohol**  알코올 : 와인의 바디감에 영향
12.  **quality (score between 0 and 10)**  와인 품질

## 2. Model structure
4가지 모델을 비교해 본 결과, Random Forest모델을 채택하게 되었습니다.  
해당 모델의 confusion matrix는 다음과 같습니다.

![image](https://user-images.githubusercontent.com/75603262/124703810-ec8b3300-df2d-11eb-8fb6-f74c1a5d650a.png)
