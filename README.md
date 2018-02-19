# Capstone Project 1
This Capstone project for Springboard's Data Science Career Track, uses World Bank's Gender Statistics dataset, downloaded from Kaggle (original files available in world-gender-statistics.zip). 

Files  	Final_Report.pdf  and  slide_deck.pdf  cover an overview of the project.

Code in Jupyter Notebooks were written and intended to be view in this order:
  Code_part1_data_wrangling.ipynb
  Code_part2_data_story.ipynb
  Code_part3_machine_learning.ipynb
Other Jupyter Notebooks in the repo were supporting work, not directly used in the final report.

I chose to use "Contreceptive Prevalence" as both a target variable as well as a feature. I used Machine Learning Regression algorithms, including Random Forest Regressor, to evaluate whether GPD, Health Spending and Education Spending could predict Conraceptive Prevalence. I think used the same algorithms to evalute whether Contraceptive Use could predict Maternal Mortality, Teen Fertility Rate and Life Expectancy.

The best performing model found was a Support Vector Machine Regressor, used to predict Maternal Mortality based on Conraceptive use, with an error score of +-14.83.


