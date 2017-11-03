
### 분석 절차

#### -1 데이터 구조파악 str(), summary() 및 Y값 (Price) 탐색

#### -2 전처리
    * 결측치 처리 - 결측치 없음 (apply(,,is.na))
    * 이상치 처리 - Price와 CC에서 이상치 발견 (boxplot, qplot() 사용)
    * Data Set 나누기 - train, validation, test 으로 구분
    * 필터링 - 양적 변수(이산형(descrete), 연속형(continous))와 질적 변수(category)로 구분.

#### -3 데이터 탐색
    * 변수별 상관계수
    * 탐색적 시각화

#### -4 변수 결정
    * step()
    * randomForest()
    
#### -5. 분석 모형 및 평가
    * Lenear Regression
    * Lasso
    * Random Forest
    * Boost
