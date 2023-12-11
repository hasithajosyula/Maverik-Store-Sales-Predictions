# Maverik-Store-Sales-Predictions

# Introduction

Maverik faces a complex challenge in forecasting sales performance for upcoming new stores. Making accurate predictions requires thoroughly examining the many influences on four key sales metrics: in-store retail, food service, unleaded fuel, and diesel. 

Simply projecting numbers is insufficient. Maverik must navigate a dynamic landscape shaped by internal initiatives like marketing and external factors such as competition and economics. Each sales category also brings unique intricacies. In-store retail may depend on layout, promotions, and inventory. Food service can hinge on menu, pricing and changing consumer preferences. Fuel sales are tied to pricing, regional driving habits, and environmentalism.

To meet this multifaceted challenge, Maverik needs an adaptive, holistic approach combining advanced analytics, market research, and industry expertise. Predictive models must incorporate real-time data to account for a retail landscape in continual flux. 

By unraveling the nuances driving each sales metric and understanding the interplay of internal and external forces, Maverik can enhance forecasting accuracy. These strategic insights guide effective resource planning while positioning Maverik to respond to emerging market shifts proactively. Mastering predictive complexity is key to continued success in a highly competitive retail fuel environment.

# Business Problem

Maverik, a leading gasoline and retail convenience store chain in the western US, is expanding its footprint with plans to construct 30 new stores annually for the foreseeable future. In order to make sure these expansions are profitable Maverik predicts the revenue of new locations for its first year using a number of factors. Our challenge will be to improve this model. We will attempt to generate accurate daily sales forecasts and a sum total for these new establishments during their first year of operation. Such precise forecasting is critical for robust financial planning and ROI calculations.

To accomplish this, we will employ a blend of statistical methods, time-series analysis, and machine-learning techniques. We will analyze various data streams, including historical sales data, qualitative insights from recent store launches, and seasonality patterns. A successful project will be marked by the close alignment of our forecasts with actual sales data and ROI, minimizing any variance and thereby affirming the model's accuracy. The project is focused strictly on sales forecasting for the new stores during their first year, leaving other business aspects and future projections out of its scope. This project will be completed by November 29th, and along the way we will be checking in at milestones including data cleaning, feature engineering, model training, and evaluation.

# Project Objective

This project aims to create a sophisticated sales prediction model for upcoming Maverik new stores. By thoroughly examining the diverse factors influencing four vital sales metrics inside sales, food service, unleaded fuel, and diesel. Maverik seeks to overcome current forecasting difficulties and boost performance insights.

Main objectives:

> Identify key internal and external variables impacting new store sales, concentrating on the various metrics. 

> Construct forecasting models accounting for the complex retail environment considering elements like store design, promotions, consumer preferences, economics, and competition dynamics.

> Identify seasonality and consumer behavior trends over the years.

> Refine predictive capabilities to boost accuracy and reliably inform resource planning, inventory logistics, and strategic initiatives. 

By creating a responsive, data-driven forecasting tool that unravels sales metric nuances, this project aims to equip Maverik with advanced insights, positioning the firm to navigate retail complexity and drive measurable growth.

# Your group's solution to the business problem

The datasets is intricately distributed across multiple tables, each representing a factor instrumental in Maverik's understanding of customer behavior. Our primary challenge was discerning the pivotal features crucial for predicting forecasts for new stores. To surmount this hurdle, we initiated the process with Exploratory Data Analysis (EDA) and formulated hypotheses derived from both intuition and EDA findings.

Addressing the challenge of missing values, we implemented data imputation strategies. Simultaneously, Feature Engineering was undertaken to eliminate redundant or insignificant predictors, while crafting new features tailored to our specific requirements. To tackle the imbalance in the target variable, a combination of undersampling and oversampling techniques was executed. Diverse models were employed for training and forecasting target variables, with the RMSE (Root Mean Square Error) serving as our evaluation metric. The repository contains comprehensive code and model comparisons.

Our primary objective was to construct a predictive model for forecasting sales in upcoming stores, utilizing a dataset with diverse predictors for 30 stores. Data preprocessing involved outlier removal, imputation for missing entries, and the conversion of categorical variables into dummy variables. Once the refined dataset was prepared, it was divided into training and testing sets. Through K-fold cross-validation, models underwent hyperparameter tuning, resulting in the development of three models: XGBoost, Prophet, and ETS (Exponential Triple Smoothing).

During model assessment, RMSE was employed as the performance metric, leading us to identify the top-performing model among the three, which is the XGBoost model. To further enhance performance, hyperparameter tuning was conducted, solidifying the XGBoost model as the most effective. In light of these results, we recommend Maverik adopt the XGBoost model for forecasting the sales of new stores, as it has consistently demonstrated superior performance metrics throughout the evaluation process.

# Your contribution to the project

I made key contributions in exploratory data analysis and modeling over the course of this project. Working closely with the team, I participated in weekly brainstorming meetings to unpack the complexities within the data. A central part of my role involved investigating connections between the target variable and predictor variables - an essential component of our project's structure. Additionally, I helped construct predictive models and compute vital performance metrics like RMSE and MAPE. I also engineered features by carefully evaluating their significance - modifying influential attributes to refine the model. Through deliberate analysis and transformation of important inputs, I aimed to boost model quality. With both statistical analytics and engineering, I played an integral part in unraveling this challenging dataset to inform our forecasting approach.

# The business value of the solution

The XGBoost predictive sales model provides significant strategic value to Maverik beyond accurate demand forecasts. By reliably anticipating sales for new stores, Maverik can optimize financial planning, allocate resources efficiently, make data-driven expansion decisions, proactively respond to market shifts, mitigate risks, boost operational effectiveness, enhance customer experiences, and maintain competitive advantage. Adoption of advanced analytics like XGBoost empowers Maverik to maximize profitability, return on investment, and long-term growth opportunities across its retail network.

# Difficulties that your group encountered along the way

Over the course of this time series project, our team encountered multiple obstacles, which includes data quality issues, complex seasonal fluctuations, difficulties selecting optimal models, constraints from minimal historical data, external drivers of sales volatility, computational resource limitations, decoding complex model outputs; and the need for regular model upkeep. 

Addressing these hurdles required diligent analysis, cooperative troubleshooting, and clear communication among team members. While time series modeling poses innate complexities, our teams joint dedication and creative problem-solving were integral to the project's ultimate success. This underscored the importance of adaptability and a commitment to ongoing learning when unraveling intricate temporal dynamics. Despite arising challenges, our resilience and collaborative spirit enabled us to overcome key barriers culminating in analytical victory.

# What you learned in the project

Participating in the Maverik analysis project furnished me with highly valuable expertise. It instructed me on effectively managing extensive datasets, addressing outliers and missing values, and handling imbalances within datasets. I developed the proficiency to employ techniques such as undersampling and oversampling to rectify data imbalances and potential biases. Additionally, I delved into the intricacies of XGBoost, Prophet, and Exponential Triple Smoothing (ETS) models, expanding my data science knowledge beyond my initial understanding. This deepened my comprehension of data science and facilitated the refinement of my skillset.

Beyond the technical aspects, I gained priceless experience in teamwork and adept communication within a group, particularly when navigating tight project deadlines. These invaluable lessons will illuminate our path in future endeavors, empowering us to adeptly apply predictive analytics to a diverse array of business challenges across various industries.
