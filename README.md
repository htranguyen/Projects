# Data Analytics Portfolio
<a name="about"></a>
## About me

Hey there! I'm Tra, currently on my journey to complete my MSc in Business Analytics at Babson College. My time here has been all about building a solid foundation in analytics and strategy, and I've got a real passion for using data to dig up those hidden insights.

During my studies, I've had the chance to dive deep into complex data, honing my knack for spotting patterns and trends. I've also gained practical experience in consulting, strategic finance, pricing strategies, data management, and statistical analysis, all of which I believe will prove invaluable in my endeavor to assist businesses in making well-informed, data-driven decisions.

This portfolio is my way of showcasing what I can do and keeping track of my journey in the data analytics field. Let's dive in! 📊🚀

[Here's my resume](Tra-Nguyen_Resume.pdf).

## List of Projects and Skills

- Descriptive statistics and predictive modelling using R
  - [House Prices Prediction - Advanced Regression Techniques (Machine Learning Project)](#houseprice)
  - [Airbnb New User Booking Location Prediction (Machine Learning Project)](#airbnb)

- Data visualization using Tableau
  - [My Tableau Public](https://public.tableau.com/app/profile/tra.nguyen4620)
 
- Data extraction and transformation using SQL

- Contact
  - Email: ng.huongtra202@gmail.com

## Project Details
<a name="houseprice"></a>
### 1. House Prices Prediction
**Code:** [House Prices Prediction.R](https://github.com/trahnguyen/Codes/blob/81feb2b02a4a77348dd95cd5b476ad96883389ab/House%20Price%20Prediction_Code.R)

**Goals:** 
1. Feature engineering
2. Predict house prices using advanced regression techniques and stacked models

**Description:** The project focused on analyzing a dataset of 79 explanatory variables describing every aspect of residential homes in Ames, Iowa. This project encompassed a comprehensive analysis of residential property data, involving data preparation, exploratory analysis, multivariate analysis, and machine learning to predict house prices accurately.
4 machine learning algorithms employed: linear regression, regression tree, neural networks, and ensemble learning.

**Results:** 
- I conducted data cleaning for improved model efficiency and accuracy, addressing "NAs" and unnecessary variables. This reduced mean absolute percentage errors for linear regression and regression tree models.
- The neural network model performed poorly with a high RMSE and MAPE.
- My ensemble model, combining linear regression, regression tree, and neural network, achieved the best RMSE and MAPE results, enhancing prediction accuracy.

<a name="airbnb"></a>
### 2. Airbnb New User Booking Location Prediction
**Code:** [Airbnb New User Bookings.R](https://github.com/trahnguyen/Codes/blob/1cdc0dcb28aee2619cc6f0ca5ecf599717c8657f/Airbnb.R)
**Slide deck:** [Airbnb New User Booking Model Results](https://www.canva.com/design/DAFujFboeaQ/6xI6QjbtAJ8MkD8YNBA7ew/view?utm_content=DAFujFboeaQ&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)

**Goals:** 
1. Data imbalance solutions
2. Predict new bookings locations using decision trees and boosting

**Description:** The core objective of this project was to enhance user experience by predicting the initial booking destinations of new users. This prediction serves multiple purposes, including the delivery of tailored content to the Airbnb community, reducing the average time it takes for users to make their first booking, and enhancing demand forecasting accuracy. The project utilized decision tree and boosting techniques to forecast new booking locations.

**Results:** 
- Challenges Addressed: The dataset had imbalances in certain variables, and the Session dataset covered only 35% of the training data.
- Key Findings: The primary booking destinations were 'NDF' and the United States. User age and sign-up method were identified as key factors influencing booking destinations.
- Recommendations: Based on model results, improvements are needed for more accurate predictions in future Airbnb user bookings analysis. 
In summary, this analysis informs on predicting Airbnb user booking destinations, highlighting data cleaning and the role of age and sign-up method while suggesting areas for future enhancements.

### 3. Junk Removal Company Operational Analysis & Optimization
**Code:** [Data Cleaning and Transformation.R](https://github.com/trahnguyen/Codes/blob/ec6c2d819e74a979c58fa94dbb6b992fb0534fe5/Junk%20Removal%20Company%20Operations%20Analysis%20%26%20Optimization)

**Goals:** Implement an optimized staff allocation system for efficient scheduling based on job distances and service types.

**Description:** 3-month project consulting a junk removal company operating in 2 states. Worked with the CEO to identify 3 key business problems. Performed data preprocessing, cleaning, and consolidation of the company's OMS, marketing data (social media, calls and leads records), and financial data. Conducted exploratory data analysis (EDA) and integrated them with field service KPIs to assess operational efficacy and areas for enhancement. Utilized R and text-processing packages to automate data cleaning process, eliminating manual errors. Compiled a report and presented to the founder with 4 strategic recommendations.

**Skills:** data cleaning, text-processing, data transformation, aggreagate functions, join functions, route optimization, performance measurement, data visualization.

**Technology:** R, tidyverse, dplyr, tidyr, tidygeocoder, stringr, psych, textclean, qdapRegex, Hmisc, lavaan, lubridate, geosphere, readxl, magrittr

**Results:** Increase revenue by $300K+ annually through enhanced staffing, scheduling, and routing strategies, enabling at least one additional field service trip per day. Devised a method to increase projected growth by 124% without requiring additional resources.
