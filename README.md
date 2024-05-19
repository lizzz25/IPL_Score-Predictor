# IPL_Score-Predictor
This Streamlit webapp enables user to predict total runs between teams using current runs and wickets.

Algorithms used:

Linear Regression
K-Nearest Neighbor Regressor
XGBoost Regressor
RandomForest Regressor
SVR
Decision Tree Regressor
Hyperparamter Optimization:

Used optuna for paramter optimization.

Dataset:

The dataset comprises of over by over details of matches and runs from 2008 to 2020.

Dataset Used: ipl_data.csv

1. mid - match id
2. date - when matches are played
3. venue - place where matches aew played
4. bat_team - batting team
5. bowl_team - bowling team
6. batsman - batsman
7. bowler - bowler
8. runs - runs scored
9. wickets - wickets
10. overs - overs - next 3 are based on this
11. run_last_5 - runs scored in last 5 overs
12. wicket_last_5 - wickets in last 5 overs
13. stricker - batsman playing as main 1
14. non-striker - batsman playing as runner up - not main 0
15. total - total score (target variable)


Use Case:

<img width="560" alt="image" src="https://github.com/lizzz25/IPL_Score-Predictor/assets/92105352/6115e0de-6d64-4582-a871-e3dd6b15f80b">

