# wannabe-badminton-stats
This project is a notebook containing some exploratory analysis of professional badminton and training some models to predict the win rate and try to gain some insight. Specifically, the data is used is data from the Badminton World Federation Tournament series. The specific dataset used is found here https://www.kaggle.com/datasets/sanderp/badminton-bwf-world-tour. In the notebook, we clean up the data and then answer some questions that can be asked about the data. For example, whether some regions are stronger than others, whether games in the finals were more likely to have closer margins and etc.  Lastly, we build a pipeline and fit a logistic regression model and a decision tree classifier. 

In this notebook, we use primarily pandas for the data manipulation, matplotlib and seaborn for the plotting, and lastly scikitlearn for the models and the pipeline. 

Improvements that can be made:
- Remove highly correlated or not very useful features
- Try more models
