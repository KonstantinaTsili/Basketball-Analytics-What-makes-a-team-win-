# Basketball Analytics : What makes a team win?

This project serves as the final project for the Machine Learning course taken at CentraleSupélec. The dataset basketball.sqlite can be downloaded from  https://www.kaggle.com/datasets/wyattowalsh/basketball. The dataset was used to analyze the game statistics that determined outcomes and points scored. Hence, there is both a Regression Task and Classification Task. The scope of the project was limited to NBA seasons starting the year 2015.

## Authors
The project is done by [Karim El Hage](https://github.com/karimelhage), [Konstantina Tsilifoni](https://github.com/KonstantinaTsili), [Firas Abo Mrad](https://github.com/Firas-AM)

<a href="https://github.com/KonstantinaTsili/Basketball_Analytics_What_makes_a_team_win
/graphs/contributors"> 
  <img src="https://contrib.rocks/image?repo=KonstantinaTsili/Basketball_Analytics_What_makes_a_team_win" />
</a>

## Project Tasks
1 - Data Setup, Extraction, Analysis, and Cleaning: As the dataset is an SQLite, relevant csv files were extracted from the database and relevant information were merged and filtered for analysis. "Game" data is retained starting the 2015 NBA season. Hence, "Draft" and "Draft Combine" data prior to the year 1995 were filtered out. Relevent data cleaning and analysis was then conducted.

2 - Feature Engineering: Creation of new features to deal with observed collinearity between variables. All created features were kept straightforward to not steer from the main objective of the project.

3 - Modeling, Evaluation, and Comparison: Implementation of Linear Regression (For Regression Task), Logistic Regression (For Classification Task), XGBoost, basic Neural Network (for interpretability). 

4- Conclusion and Findings: Select models were used for feature importance interpretability to determine the game statistics that contirbuted most to the objectives. The findings can be found in Report-NBA_Analytics-_What_Makes_Teams_Win.pdf
