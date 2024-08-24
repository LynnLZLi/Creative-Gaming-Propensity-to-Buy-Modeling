# Creative-Gaming-Propensity-to-Buy-Modeling

#### Project Overview:
In this project, I was tasked with developing a predictive model for Creative Gaming, aimed at identifying which players of the game "Space Pirates" were likely to purchase the Zalon campaign. This involved extensive data analysis, model training, and evaluation to predict player behavior and optimize marketing strategies effectively.

#### Data Preparation and Exploratory Analysis:
- **Dataset**: Utilized a dataset named "data/cg_organic.parquet" containing telemetry data of 30,000 Space Pirates gamers.
- **Exploratory Analytics**:
  - Calculated the organic conversion probability to the Zalon campaign.
  - Generated descriptive statistics for each feature, identifying numeric and categorical data characteristics.
  - Created visualizations like histograms for numeric variables and frequency plots for categorical variables to understand data distribution.

#### Predictive Modeling:
- **Model Training**:
  - Trained a logistic regression model using the 'training' flag to distinguish between training and testing data.
  - Identified key features influencing the likelihood of purchasing the Zalon campaign through exploratory variable analysis.
- **Model Evaluation**:
  - Calculated and plotted gains curves for both the training and test datasets.
  - Reported the model's performance using the Area Under the Curve (AUC) metric for both datasets.

#### Ad-Experiment Analysis:
- **Setup**:
  - Conducted an ad-experiment involving 180,000 customers divided into three groups to test the effectiveness of in-app ads and predictive modeling.
- **Group Analysis**:
  - Calculated conversion rates and profits for three different groups—those who saw no ads, those who were randomly shown ads, and those targeted based on the predictive model.
  - Analyzed the impact of the ad campaigns and predictive model on conversion rates and profits, providing actionable insights to Creative Gaming.

#### Model Retraining and Evaluation:
- **Retraining**:
  - Retrained the logistic regression model using data from customers exposed to ads, integrating new insights and data patterns.
- **Performance Comparison**:
  - Compared the original model and the retrained model's performance using AUC and gains curves, demonstrating the benefits of model updates based on the latest data.

#### Advanced Predictive Techniques:
- **Neural Network and Random Forest Models**:
  - Applied advanced machine learning techniques such as neural networks and random forests to further refine predictions.
  - Evaluated and compared these models to the logistic regression model, determining which model provided the best performance in terms of prediction accuracy and profitability.

#### Key Accomplishments:
- **Effective Predictive Model Development**:
  - Developed models that accurately predict customer behavior, enabling Creative Gaming to tailor their marketing strategies effectively.
- **Insights from Data Analytics**:
  - Delivered deep insights into player behavior and the effectiveness of promotional strategies, facilitating data-driven decision-making.
- **Enhancement of Marketing Efficiency**:
  - Demonstrated how targeted advertising based on predictive analytics could significantly improve conversion rates and profits, maximizing marketing ROI.

#### Technologies and Tools Used:
- **Data Analysis and Modeling**: Python, pandas, pyrsm, logistic regression, neural networks, random forests.
- **Data Visualization**: Matplotlib for generating histograms and gains curves.
- **Version Control and Collaboration**: Utilized Git and GitHub to manage code and collaborate with team members.
