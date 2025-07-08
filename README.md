# 📊  World Population

## 🗃️ Dataset
- Source: https://www.kaggle.com/datasets/gemartin/world-bank-data-1960-to-2016?resource=download 
- Three datasets related to country population, fertility rate and life expectancy up to 2016, available in the World Bank Data.

## 🎯  Aim 
Make a prediction Model for predicting these 3 variables. 

## 🔍 Objectives
Produce a model to be TESTED for 10 randomly selected countries to make predictions for 2017, and optionally for 2018.
Compare the results with actual historical data from the World Bank Site.

## 🛠️ Tools
- Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, etc.)
- Jupyter Notebook

## 📈 Methodologies
1. **Exploratory Data Analysis (EDA)**
2. **Transform into Stationary Data**
3. **SML Model Training**
4. **Predictions**
5. **Discussion**

## 💡 Findings
- It is generally not appropriate to use machine learning to make predictions about specific future events, such as the population of a particular country in a specific year - machine learning models are based on patterns and trends in data, and are not able to take into account unforeseeable events or changes that may affect the outcome of the prediction.
- Data was transformed in a way to make it stationary by eliminating (or reducing) patterns: 4 deltas (time-difference values) and 8 deltas as variables to assess the models.
- Some SML models were trained and tested for 10 countries in order to make predictions for 2017.
- The models performed well, especially for the country population dataset and fertility rate, but not so well for life expectancy.
- How data is process has a significant impact on the models: the model improved when using more variables.
- When checking for the real data for 2017, most of the predictions are far from the reality, even though the models have a god fitting.
- A model to predict data for 2018, applying a time-difference (delta) of two years lag, as 4 or 8 variables was also trained.
- The trained models showed a good performance, better when using more variables, but again the predictions were not amazing when compared to the real values of country population, life expectancy and fertility rate for 2018 of the randomly selected countries.
- This poor performance of the machine learning model on the 2017 data in the dataset of population, fertility rate, and life expectancy by country is likely due to a combination of factors: insufficient or limited data to accurately predict trends in 2017.
- Country population, life expectancy and fertility rate are affected by many unpredictable variables that are different depending on the country.
- Those variables were not considered to build a multivariate model, that might be one of the causes of the poor predictions observed.
- A single model to predict the three target variables could have been assed, applying methods as neural networks, that can handle the prediction of multiple outputs.
- Some geographic variables, together with average income, diet, country’s gross domestic product, etc, could also help to build a better model. 

## 📄 [View Project Report](https://drive.google.com/file/d/1_OwFx87Qzdtgyc1XSpyRPwlnl2CZT4Jz/view?usp=sharing) 
