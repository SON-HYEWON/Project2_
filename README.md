# 🍷 Wine Planning with ML
<img width="400" alt="21644_9286_1129" src="https://user-images.githubusercontent.com/75603262/133894972-dfdeccd2-bccf-4031-8285-12010c8d56d4.jpeg">
기존에 존재하는 와인데이터를 바탕으로 해서, 새롭게 들어올 와인에 대한 점수를 예측하는 모델을 제작하였습니다.  

[이미지 출처](http://www.travie.com/news/articleView.html?idxno=21644)

## 1. 기획 배경
- 최근 코로나의 여파로 `혼술/홈파티족`이 생겨나면서, 와인 입문자가 증가하는 추세입니다.
- 와인 입문자가 와인을 선정하는 데에 있어서 가장 손쉬운 비교 법은 `와인 평가 점수`를 살펴보는 일일 것입니다.  
  다시말해, 이들에게 `와인 평가 점수`라는 것은 와인을 선택하는 데에 중요한 척도 중 하나인 것입니다.
- 이러한 `와인 평가 점수`를 ML을 통해 예측하는 것이 이번 프로젝트의 목표입니다.

## 2. DataSet
[해당 링크](https://www.kaggle.com/rajyellow46/wine-quality)의 데이터 셋을 이용했습니다.  

## 3. Model Evaluation
4가지 모델을 비교해 본 결과, 정밀도가 가장 높은 `Random Forest`모델을 채택하게 되었습니다.  
해당 모델의 confusion matrix는 다음과 같습니다.  
<img width="400" alt="image" src="https://user-images.githubusercontent.com/75603262/124703810-ec8b3300-df2d-11eb-8fb6-f74c1a5d650a.png">

## 4. 프로젝트 정리
- [프로젝트 발표 자료 링크](https://github.com/hyewonsonn/Project2_Wine-planning/blob/main/AI_02_%E1%84%89%E1%85%A9%E1%86%AB%E1%84%92%E1%85%A8%E1%84%8B%E1%85%AF%E1%86%AB_Section2.pdf)
- [프로젝트 발표 영상 링크](https://youtu.be/bjk9DvrkOCg)
