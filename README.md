# Multiple Linear Regression to Predict Rice Production
This project analyzes the relationship between agricultural variables, such as harvested area, and climatic factors, such as rainfall, temperature, and humidity, on rice production in Sumatra. It employs multiple linear regression to develop a predictive model for rice production, providing actionable insights for policymakers and stakeholders.

## Table of Contents
1. [Background](#background)
2. [Data Overview](#data-overview)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Conclusion](#conclusion)
6. [Recommendations](#recommendations)
7. [Tools Used](#tools-used)
8. [Link to Google Colab and Slide](#link-to-google-colab-and-slide)

---

## Background
Indonesia is one of the largest rice producers globally, with rice being the staple food for its population. This project aims to:
- Analyze the impact of climate variables on rice production.
- Develop a predictive model using multiple linear regression to assist in agricultural planning and resource allocation.

---

## Data Overview
The dataset consists of 224 entries from different regions in Sumatra, including:
- **Provinsi** (Province)
- **Tahun** (Year)
- **Produksi** (Rice Production, kg)
- **Luas Panen** (Harvested Area, ha)
- **Curah Hujan** (Rainfall, mm)
- **Kelembapan** (Humidity, %)
- **Suhu Rata-rata** (Average Temperature, °C)

---

## Methodology
1. **Data Cleaning**:
   - Verified the dataset had no missing or duplicate values.
2. **Exploratory Data Analysis (EDA)**:
   - Strong correlation observed between harvested area and rice production (r = 0.91).
   - Weak correlations between climatic factors and production.
3. **Model Building**:
   - Applied multiple linear regression using:
     - **X1**: Rainfall
     - **X2**: Humidity
     - **X3**: Average Temperature
     - **X4**: Harvested Area
   - Dataset split: 80% training, 20% testing.

---

## Results
- **R-squared**: 0.8698 (86.98% of the variance explained by the model).
- **Mean Squared Error (MSE)**: 115,079,741,001.90.
- Key findings:
  - Harvested area significantly impacts rice production positively.
  - Rainfall has a small positive impact.
  - Humidity and temperature negatively impact rice production.

---

## Conclusion
The study highlights the critical role of agricultural and climatic variables in rice production. The findings emphasize the need for climate adaptation strategies and efficient resource management to ensure stable rice production in the face of changing environmental conditions.

---

## Recommendations
- Collect additional data (e.g., soil quality, irrigation practices) for improved accuracy.
- Experiment with advanced models (e.g., Random Forest, Gradient Boosting).
- Develop strategies to mitigate the effects of climate change on agriculture.

---

## Tools Used
The following tools and libraries were used in this project:

### Programming Language and Libraries
- **Python**:
  - `pandas`: For data manipulation and analysis.
  - `numpy`: For numerical computations.
  - `matplotlib`: For creating static, animated, and interactive visualizations.
  - `seaborn`: For statistical data visualization.
  - `scikit-learn`:
    - `LinearRegression`: To build the multiple linear regression model.
    - `train_test_split`: To split the dataset into training and testing subsets.
    - `mean_squared_error` and `r2_score`: For evaluating model performance.

### Tools
- **Google Colab**: To run and share the notebook interactively.

---

## Link to Google Colab and Slide
- [bit.ly/RiceProduction](https://bit.ly/RiceProduction)
- [bit.ly/RiceProduction_slide](https://bit.ly/RiceProduction_slide)
