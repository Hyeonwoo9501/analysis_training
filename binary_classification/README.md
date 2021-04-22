# analysis_training
 

## 목적
세개의 csv파일을 이용해서 제품(자동차)의 maintenance failure를 예측한다.


## csv file descriotion
1. failure.csv : 제품 키번호와 failure의 유무가 기록되어 있는 dataset
2. maintenance.csv : 제품 키번호, 사고발생이유와 Quantity가 기록되어 있는 dataset
3. usage.csv : 서비스를 받기 시작하고 time stamp별 사용한 양이 기록되어 있습니다.



## Training
 - 예측 변수 : failure_bin
 - 설명 변수 : 그외 다른 변수
 - RandomForest 사용
 
