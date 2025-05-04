# 🏡 Housing Price Prediction

This repository contains a regression analysis project to predict housing prices using various machine learning techniques including a custom implementation of Linear Regression and a Decision Tree Regressor from scikit-learn.

---

## 📁 Project Structure

```

.
├── Task04.ipynb           # Main notebook with data preprocessing, model training & evaluation
├── HousingData.csv        # Dataset used for regression analysis
├── README.md              # Project documentation

````

---

## 📊 Dataset

The dataset used is `HousingData.csv`, which contains the following features:
- CRIM: Per capita crime rate by town
- ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
- INDUS: Proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX: Nitric oxides concentration (parts per 10 million)
- RM: Average number of rooms per dwelling
- AGE: Proportion of owner-occupied units built prior to 1940
- DIS: Weighted distances to five Boston employment centres
- RAD: Index of accessibility to radial highways
- TAX: Full-value property-tax rate per $10,000
- PTRATIO: Pupil-teacher ratio by town
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town
- LSTAT: % lower status of the population
- **MEDV (target)**: Median value of owner-occupied homes in $1000s

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/housing-price-prediction.git
   cd housing-price-prediction
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook Task04.ipynb
   ```

---
🛠️ Methodology

✔️ Preprocessing

* Missing values are imputed using the **mean strategy**.
* Features are normalized using **Z-score standardization**.
* No categorical variables were found in the dataset.

✔️ Models Implemented

* **Linear Regression (from scratch)** using gradient descent
* **Decision Tree Regressor** (scikit-learn)

✔️ Evaluation Metrics

* Mean Squared Error (MSE)
* R² Score

✔️ Visualizations

* Scatter plots of actual vs. predicted values for model evaluation.

🤖 Dependencies

* numpy
* pandas
* matplotlib
* scikit-learn
* jupyter

You can install all dependencies using:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
