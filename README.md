# IPL-CricPred

## Overview

This is a sports analytics project that aims to analyze past data in order to predict future performance of participating teams in IPL(a format of cricket).
<br>
The prediction attempts to answer below queries(as motivated from a specific competition, hence the points system):

| Query | Points | Misc. |
| --- | --- | --- |
| Winning Team | 20 | Streak: N*5 points |
| Winner of Toss | 5 | |
| Player of the match | 20 | |
| Target Runs | 10 | Buckets: <100, 100-139, 140-169, 170-200, >200 |
| Winning Margin | 20 | * |
| Total Boundaries (4s and 6s) | 10 | Buckets: <20, 20-30, 30-40, >40 |
| Player # 1 | 2x | * |
| Player # 2 | 1.5x | * |
| Player # 3 | 1x | * |
| Winner of tournament | 100 | |


<hr>


## Task List

- [ ] Use kaggle data to develop a rough baseline model (and few alternatives)
- [ ] Web scrape past data
- [ ] Prepare tableau visualizations
- [ ] Data cleaning
- [ ] Improved baseline model to predict match winner
- [ ] Add mlflow based model tracking
- [ ] Add news analysis/NLP

<hr>


## Useful Links

- IPL all matches and ball by ball data (2008-2024) : https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020
- Auction Data 
- Auction Data 2025 : https://www.kaggle.com/datasets/souviksamanta1053/ipl-2025-mega-auction-dataset
