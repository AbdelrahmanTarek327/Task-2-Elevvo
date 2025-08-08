# Task-2-Elevvo
# Forest Cover Type Classification using Machine Learning

![Project Demo](results/demo.gif)

## 📜 Abstract
This project implements a machine learning model to classify **forest cover types** using a dataset from Kaggle.  
The aim is to explore **Random Forest** and **XGBoost** algorithms to accurately predict the forest cover type based on cartographic variables such as elevation, slope, soil type, and wilderness area, achieving high accuracy while maintaining generalizability.

---

## 📂 Dataset
- **Source:** [Kaggle - Forest Cover Type Dataset](https://www.kaggle.com/datasets/zsinghrahulk/covertype-forest-cover-types)
- **Size:** 581,012 rows × 55 columns
- **Description:**  
  The dataset contains cartographic variables derived from US Geological Survey data:
  - **Features:** Elevation, Aspect, Slope, Horizontal/Vertical distances, Hillshade indices, Wilderness Area indicators, Soil Type indicators.  
  - **Target:** Forest Cover Type (7 distinct classes).

---

## 🧠 Methodology
1. **Data Preprocessing**  
   - Verified no missing values  
   - Feature encoding for categorical variables  
   - Standard scaling for numerical features  

2. **Exploratory Data Analysis (EDA)**  
   - Class distribution visualization  
   - Feature correlation heatmaps  
   - Elevation vs. Cover Type scatter plots  

3. **Model Development**  
   - **RandomForestClassifier** for baseline  
   - **XGBoostClassifier** for optimized performance  

4. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-score per class  

---

## 📊 Results
| Model                  | Accuracy | Precision | Recall | F1-score |
|------------------------|----------|-----------|--------|----------|
| RandomForest           | 0.94     | 0.93      | 0.88   | 0.90     |
| XGBoost                | 0.96     | 0.94      | 0.92   | 0.93     |

> The **XGBoost model** outperformed others with the highest accuracy.
