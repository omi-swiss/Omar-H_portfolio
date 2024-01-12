# Omar's Portfolio

## Project 1: [Healthcare Analytics: Patient Length of Stay Prediction]([https://github.com/your-github-repo/healthcare-analytics-LOS-prediction)

This project delves into the realm of healthcare analytics with a focus on predicting the Length of Stay (LOS) for patients in various healthcare facilities. The Length of Stay is a crucial indicator in healthcare, impacting patient outcomes, healthcare costs, and overall hospital efficiency.

**Goal**: Our objective is to enhance patient care and optimize hospital resources by developing a predictive model for patient LOS. This model aims to provide healthcare providers with insights into potential LOS durations, allowing for better planning and resource allocation. We are working closely with healthcare data to identify patterns and factors influencing LOS.

- The data encompasses 230K patient records across various regions and hospitals, with 19 features.
- We conduct extensive exploratory data analysis (EDA) within Snowflake to understand and prepare the data.
- The project leverages AWS Sagemaker for a streamlined machine learning pipeline, enhancing the efficiency of our model development process.
- Our predictive models include Linear Regression, Random Forest Regression, and XGBoost Regression, each offering unique insights into the factors influencing patient LOS.
- Post-analysis, we integrate our model predictions back into Snowflake, enabling real-time updates and insights for healthcare providers.
- 
### Architecture  
![](Healthcare-Analytics/blob/main/Architecture%20Design.avif)

## Project 2: [Customer Propensity Model for an E-Commerce Company](https://github.com/omi-swiss/Customer-Propensity-Model)

This project is for an emerging e-commerce startup that offers a wide range of products, from daily essentials like dairy and vegetables to high-end electronics and home appliances. Despite a growing number of visitors exploring their platform, only a small fraction actually makes a purchase.

**Goal**: To boost sales without depleting their limited marketing budget, the company plans to send targeted discounts or coupons to users who are more likely to make a purchase. As a trusted partner, we were tasked with building a propensity model to predict the likelihood of individual users buying a product. This predictive model will enable the company to identify and target users with the highest purchase probabilities, ensuring a more efficient and cost-effective marketing campaign.

- Data provided by projectpro.io.
- Conducted an exploratory analysis of the dataset to ensure data quality and performed feature engineering for a more robust model.
- The model uses logistic regression and an RFM (Recency, Frequency, Monetary) analysis for customer propensity modeling.
- Optimized the logistic regression model for improved performance.

## Project 3: [Avocado Price Prediction](https://github.com/omi-swiss/ML-Price-Prediction)

This project focused on forecasting the prices of avocados in the US. We explored multiple machine learning approaches to determine the optimal model for predicting avocado prices.

**Goal**: Predict the price of avocados in the future.

- Data provided by projectpro.io.
- Conducted an exploratory analysis of the dataset to gain insights into avocado pricing trends, seasonal patterns, and regional variations.
- Performed feature engineering to create relevant features that can enhance the performance of our price prediction models.
- Utilized two time series models to predict prices: ARIMA and SARIMA.

### SARIMA Model Prediction 
![](Avocado%20Forecast%20Using%20SARIMA.png)

## Project 4: [Retail Price Optimization](https://github.com/omi-swiss/ML-Price-Optimization)

This project focused on a retail company looking to optimize the prices of their products. We analyzed restaurant sales data and applied Ordinary Least Squares (OLS) and price elasticity concepts to set ideal prices.

**Goal**: Improve profitability by optimizing prices.

- Data provided by projectpro.io.
- Conducted an exploratory analysis of the dataset to understand purchasing trends of products and gain insights into price sensitivities using linear regression.
- Used Ordinary Least Squares (OLS) to estimate the parameters of the linear regression model.
- Further optimized the analysis by incorporating price elasticity to understand how changes in price affect the quantity demanded of a product or service.

### Price Optimization Per Product
![](Price%20Optimzation%20Per%20Product.png)

---------------------------------------------
