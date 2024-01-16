# Kaggle : Lifestyle_and_Wellbeing_Data 데이터셋 분석 With python, pandas, seaborn

(https://www.kaggle.com/datasets/ydalat/lifestyle-and-wellbeing-data)
-----
- 함수 및 클래스 코드에 집중
    1) 클래스 및 함수를 사용해, 비슷한 종류의 데이터가 들어올 때, 같은 분석을 할 수 있게끔 정규화도 해보았습니다.
    2) 마지막 kmeans분석에서 일련의 과정을 통해 n을 결정하고, heatmap과 correlation을 한번에 그릴 수 있도록 했습니다.

- EDA와 p-value, kmean 방법을 가지고 분석
    1) csv 파일을 pandas를 사용해 불러온 뒤, 각 columns와 counts에 대한 그래프를 그리고, 분석. 필요한 경우, pie차트를 도입해 비율을 더 보기 편하도록 변경. 예를 들어, 데이터의 종류가 숫자가 아닌 경우, 또는 숫자더라도 2개의 숫자만 존재하는 경우에 대해 pie차트를 그리고, 비율을 표시해 좀 더 직관적으로 변경했습니다.
    2) EDA를 통해 각 column의 correlation 파악. column pair를 정해서 가설을 세움
    3) 가설에 대한 검증. column pair에서 한 column 값의 증가에 따른 다른 column의 평균에 대해 조사.
    4) kmeans을 사용해, 데이터를 그룹화
-----

