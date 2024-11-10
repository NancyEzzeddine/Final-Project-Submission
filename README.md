# Final-Project-Submission

# Automation Inequality: Predicting Global Automation Trends

## Project Overview

This project explores the global trends in automation adoption and seeks to predict future automation levels across different regions. By analyzing economic, infrastructural, and social factors, the project aims to understand and bridge the gap between automation potential and actual automation adoption, especially in developing regions. Our ultimate goal is to provide insights for policymakers and investors to support balanced global development and reduce the automation divide.

## Objectives

1. **Identify Automation’s Impact Across Industries and Regions**  
   Analyze sectors and regions most vulnerable to automation-driven job disruptions.

2. **Understand Key Drivers of Automation**  
   Examine factors like AI investment, skill levels, and economic conditions that influence automation adoption.

3. **Predict Automation Levels to Monitor Progress**  
   Develop a machine learning model to forecast automation levels across countries, allowing real-time monitoring of advancements and delays.

4. **Bridge the Global Automation Gap**  
   Provide insights to guide policy and training initiatives that reduce the divide between developed and developing regions.

## Data Sources

We used a variety of global datasets to create a comprehensive feature set for our model:

- **World Bank**: GDP per capita, governance indicators
- **International Labor Organization (ILO)**: Labor force participation rate
- **International Telecommunication Union (ITU)**: Internet penetration rate
- **UNESCO**: R&D expenditure, STEM graduates
- **UNCTAD**: ICT imports, trade as a percentage of GDP
- **DHL**: Global connectedness index
- **IMF**: Foreign direct investment (FDI)
- ...and more sources providing economic, technological, and workforce data.

All datasets used can be be access via this link (since several were too large to uploade to github): https://drive.google.com/drive/folders/1q2NaF2U7aAXaDp-WzJW9fwg8XiPGQFMF?usp=drive_link

## Methodology

### 1. Data Preprocessing
   - Cleaned and standardized the dataset for consistency.
   - Used **K-Nearest Neighbors (KNN)** to fill in missing values based on similar countries' characteristics.
   - Transformed skewed distributions and handled outliers to enhance model performance.

### 2. Feature Engineering
   - Performed **Principal Component Analysis (PCA)** to reduce dimensionality and identify the most influential features.
   - Selected top features, including global connectedness, GDP per capita, and regulatory quality, as key indicators for automation readiness.

### 3. Model Selection
   - Tested several models, including **Linear Regression, Random Forest, and Gradient Boosting**, to determine the best fit for predicting automation levels.
   - **Random Forest** showed the highest accuracy with an R² score of 0.88 and was chosen as the final model.

### 4. Model Evaluation and Improvement
   - Analyzed residuals to identify areas for potential improvement.
   - Future enhancements include refining the feature set and exploring advanced models, such as neural networks, to further improve accuracy.

### 5. Extrapolation and Analysis
   - Extrapolated future automation levels for each income group up to 2030, highlighting the growing gap between high-income and low-income regions.
   - Presented projections and policy recommendations to support equitable automation growth globally.

## Results

- **Automation Disparities**: High-income regions show significant growth in automation levels, while lower-income regions lag behind, highlighting a potential automation divide.
- **Key Drivers of Automation**: Economic indicators, such as GDP per capita and technological infrastructure, are strong predictors of automation adoption.
- **Policy Implications**: Targeted support in the form of digital infrastructure, skills training, and economic incentives is crucial for bridging the global automation gap.

## Conclusion

This project provides a predictive model that offers valuable insights into global automation trends and future projections. The findings emphasize the need for targeted interventions in developing regions to ensure balanced automation adoption worldwide. Closing the automation gap is essential to prevent deepening global inequalities and foster inclusive economic growth.

## Future Work

1. **Enhanced Models**: Explore ensemble methods and neural networks to capture complex patterns and improve prediction accuracy.
2. **Data Expansion**: Incorporate more granular data, including regional datasets, to refine predictions at a sub-national level.
3. **Policy Simulation**: Develop a framework to simulate policy interventions and their potential impact on automation adoption in underdeveloped regions.
