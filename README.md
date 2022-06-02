# aichallenge_water


## 🔎 Overview
###### https://aichallenge.or.kr/competition/detail/1/task/10
<br>

### 과제 설명  
- 수질에 영향을 미치는 6개 요인의 시계열 수치를 예측하는 문제<br>
<br>

### 추진 배경
- 최근 녹조 현상 심화에 따라, 수질 오염의 사회경제적 비용 및 생태계에 미치는 영향에 대한 관심이 증대됨
- 수질오염 요인 악화에 대한 선제적 대응을 위해서는 오염원의 시계열에 대한 정확한 예측이 요구됨
<br><br>

### 평가지표: RMSE(Root Mean Squared Error)
<br>

###  데이터 이해
- pH(수소이온농도): 
- COD(화학적산소요구량)
- SS(부유물질)
- N(총질소)
- P(총인)
- T(채수기온도)

#### factor 조합 별 standard scaling (z-score)을 적용했다. 

~ 2018년


2010 ~ 2018: 데이터 학습

2018 ~ 2020 데이터를 추측(예측) 모델이. -> 제출하게되면  -> 평가지표(성능)