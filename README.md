# 🚢 Titanic Survival Prediction

This project is a complete exercise in **data processing and analysis**, including preparation, visualization, and application of **supervised Machine Learning algorithms** on the Titanic dataset.  
It follows an iterative process to explore the data, prepare it for modeling, and train various classification models to predict passenger survival.

---

## 🛠️ Technologies Used

- 🐍 **Python**: Programming language for data processing and analysis  
- 📊 **Pandas**: Data manipulation using DataFrames  
- 🔢 **NumPy**: Numerical matrix operations and statistical calculations  
- 📈 **Matplotlib** & **Seaborn**: Data visualization tools  
- 🤖 **Scikit-learn**: Machine Learning model training and evaluation  
- 🔍 **Grid Search**: Hyperparameter tuning to optimize model performance  

---

## 🔄 Project Phases

### 📥 Phase 1: Importing Libraries

Import all required Python libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`) for data processing and modeling.

### 📂 Phase 2: Loading the Data

- Load the Titanic dataset (`train.csv`)  
- Display the first few rows and inspect data structure  
- Clean the data: handle missing values and convert categorical variables into numeric ones

### 📊 Phase 3: Data Exploration & Visualization

- Analyze correlations between features (e.g., sex, class, age) and survival  
- Generate plots using `Seaborn` and `Matplotlib` to identify visual patterns  
- Examples:
  - Survival rate by gender 👩‍🦱👨
  - Influence of passenger class 🛳️

### 🧹 Phase 4: Data Preparation for Modeling

- Split data into features (`X`) and target (`y`)  
- Normalize feature values  
- Split the dataset into training and testing sets using `train_test_split`

### 🤖 Phase 5: Modeling with Supervised Machine Learning

- 📍 **K-Nearest Neighbors (KNN)**: Classifies based on closest data points  
- 🌳 **Decision Tree**: Creates a tree-like model of decisions  
- 🌲 **Random Forest**: Uses multiple trees for better performance

> Each model is trained and tested to predict passenger survival.

### ⚙️ Phase 6: Model Optimization with Grid Search

- Use `GridSearchCV` to find the best hyperparameters  
- Tune:
  - `n_neighbors` for KNN
  - `max_depth` for Decision Tree

### 📈 Phase 7: Model Evaluation

- Evaluate model performance using:
  - 🎯 Accuracy  
  - 🎯 Precision  
  - 🔁 Recall  
  - 🧮 F1 Score  
- Compare performance of KNN, Decision Tree, and Random Forest to select the best model

---

## ✅ Results & Conclusion

This notebook provides insights into the Titanic dataset and applies advanced Machine Learning techniques to predict survival outcomes.  
Using **Grid Search** improved model performance significantly.  
The final model was selected based on the **highest evaluation scores** on the test set.

---

## 📎 Example Visualization

![Sample Graph](https://upload.wikimedia.org/wikipedia/commons/4/41/Matplotlib_logo.svg)

---

## 📁 Project Structure

```bash
├── titanic_survival_analysis.ipynb
├── train.csv
├── README.md
└── models/
