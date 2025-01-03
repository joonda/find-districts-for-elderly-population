# Find Districts for Elderly Population

## Summary
* Find districts in Korea for elderly population.
* used quantitative indicators that had representitive, and each indicaotrs granted weight.
* if you need conclusion, go to conclusion.ipynb file in conclusion folder.

## Project Purpose
* As time goes by, aging becomes more severe, In korea, aging index reached 17% in 2023
* According to Statistics Korea expect aging index will reached 36% in 2050.
* Provides more substantive and specific information through a quantitative approach.

## Data
* Used public data
* The data used for analysis is easily found each ipynb files in preprocessing folder (url)

## Indicators (Weight)
* Medical (30%)
* Apartments (20%)
* Traffic (20%)
* Culture (15%)
* Welfare (15%)

## Statistics
* Shapiro-wilk Test
* P-value
* z-score, t-score
* Robust Scaler
* Boxcox transform
* log transform

## Top 5 districts
* 중구
* 종로구 
* 용산구
* 강남구
* 서초구

## Bottom 5 districts
* 중랑구
* 금천구
* 관악구
* 은평구
* 도봉구

## Conclusion
* Top 5 districts are score highly in Medical and Traffic categories. In particular 중구 and 종로구 are making efforts to provide diverse cultural environments.
* The bottom 5 districts stand out for their lack of cultural and welfare infrastructure, In particular 은평구 and 도봉구 need to improve their overall environments.
* The successful cases of the top 5 districts should be applied to the bottom 5 districts to systematically address their lack of infrastructure
* By regularly updating data and conducting additional studies on various factors, more concrete and practical policy implications are expected to be suggested.