# Purwadhika Capstone 3
Saudi Arabia Used Cars Price Prediction
--- 
This repository utilizes the Machine Learning Modelling Process for Module 3 as a part of the Digital Talent Incubator (DTI) learning process by Purwadhika.

--- 
`Business Context` <br>

The used car market in Saudi Arabia is a significant contributor to the automotive industry. Economic conditions and cultural preferences drive consumer preference for used cars, which offer competitive pricing and accessible financing options. Online platforms like Syarah.com streamline transactions, providing transparency and a diverse range of vehicle choices, from practical everyday cars to luxurious SUVs. Market participants employ competitive pricing strategies to meet diverse consumer demands, ensuring robust growth and sustained high demand in the Saudi Arabian used car market.

As reported by [Mordor Intelligence](https://www.mordorintelligence.com/industry-reports/saudi-arabia-used-car-market), it is forecast that Saudi Arabia's used car market will continue to experience high demand in the future, it is therefore vital to use a machine learning model to forecast used car prices in order to optimise pricing strategies, enhance market transparency and empower buyers and sellers in the Saudi Arabian market to make well-informed decisions.

`Market Overview`
1. **Market Dynamics:** <br>
The demand for used cars in Saudi Arabia is influenced by factors such as affordability, depreciation rates, availability of financing options, and preferences for specific brands and vehicle types.
   
2. **Consumer Behavior:** <br>
Saudi consumers often prefer well-maintained used cars that offer value for money. The market includes a variety of vehicle types ranging from compact cars to luxury SUVs, catering to diverse consumer segments.

3. **Online Platforms:** <br>
Websites such as Syarah.com are essential to the Saudi used automobile market. These marketplaces make it easier to purchase and sell cars by providing comprehensive listings, comparing features, and an easy-to-use interface. They offer accessibility and transparency to a variety of vehicle options in various locations.

`Goals`

The objective is to develop a predictive model based on multiple factors that can accurately anticipate used automobile prices in Saudi Arabia. By offering reliable pricing predictions, this model will assist buyers and sellers in making well-informed decisions, thereby enhancing efficiency and transparency in the used automobile market.

`Analytical Approach`

To achieve these goals, a comprehensive analytical approach will be implemented, encompassing data collection, preprocessing, exploratory data analysis, feature engineering, model selection, training, evaluation, and deployment. The key steps in this approach are outlined below:

1. **Data Collection:**
   - **Data Sources:** The dataset includes the following attributes: Type, Region, Make, Gear Type, Origin, Options, Year, Engine Size, Mileage, Negotiable, and Price. The dataset contains 5624 records of used cars collected from syarah.com

2. **Data Preprocessing:**
   - **Data Cleaning:** Handle missing values, outliers, and inconsistencies in the dataset. Ensure data quality by standardizing formats and correcting inaccuracies.
   - **Data Transformation:** Convert categorical variables (e.g., Make, Region, Gear_Type) into numerical representations using techniques like one-hot encoding or label encoding. Scale numerical features (e.g., Mileage, Engine_Size) to ensure uniformity and improve model performance.

3. **Exploratory Data Analysis (EDA):**
   - **Descriptive Statistics:** Generate summary statistics to understand the distribution and central tendencies of the data.
   - **Visualizations:** Use visualizations (e.g., histograms, scatter plots, box plots) to identify relationships between variables, detect patterns, and gain insights into data distribution and correlations.

4. **Feature Engineering:**
   - **Feature Selection:** Identify and select relevant features that have a significant impact on the target variable (Price). This may include deriving new features from existing ones (e.g., age of the car from the Year attribute).
   - **Feature Importance:** Utilize techniques like correlation analysis, mutual information, and feature importance from tree-based models to assess the importance of different features.

5. **Model Selection and Training:**
   - **Algorithm Choice:** Consider various machine learning algorithms such as Random Forest, Gradient Boosting, and XGBoost for regression tasks. Ensemble methods can also be explored to improve predictive performance.
   - **Hyperparameter Tuning:** Employ techniques like GridSearchCV and RandomizedSearchCV to optimize hyperparameters for the chosen algorithms. Utilize cross-validation to ensure robust model evaluation.

6. **Model Evaluation:**
   - **Performance Metrics:** Evaluate model performance using metrics like Mean Absolute Percentage Error (MAPE) and Adjusted R-squared (Adjusted R2). These metrics will help assess the accuracy and reliability of the predictions.
   - **Model Validation:** Perform validation on unseen data to ensure the model generalizes well to new data and avoids overfitting.

7. **Model Deployment:**
   - **Integration:** Integrate the predictive model into the Google Cloud Platform (GCP)
   - **Monitoring and Maintenance:** Continuously monitor the model’s performance and update it with new data to maintain its accuracy over time. Implement feedback loops to refine the model based on user interactions and market changes.

By following this analytical approach, the predictive model will provide accurate and reliable used car price predictions, benefiting both consumers and industry stakeholders in the Saudi Arabian market.

`Outcome`<br>

By accurately predicting used car prices, stakeholders can:
- Stakeholders can improve their ability to make decisions by enabling sellers to set competitive rates based on vehicle condition, market trends, and other factors when used car prices are accurately predicted. This is accomplished by giving dealers the ability to accurately estimate used automobile pricing.
- Enhance the customer experience by giving customers the information they need to make educated decisions about what to buy that suit their needs and budget.
- Enhance Inventory Control by Dealers and online platforms can optimize their pricing and inventory strategies by utilizing predictive analytics.
