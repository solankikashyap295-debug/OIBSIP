# 📈 Sales Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting product sales using Machine Learning techniques. By analyzing advertising expenditures across different marketing channels, the model learns the relationship between advertising budgets and sales performance.

The project uses data preprocessing, feature analysis, and Linear Regression to build a predictive model capable of estimating future sales based on advertising investments.

---

## 🎯 Objective

To develop a machine learning model that accurately predicts product sales based on advertising spending across various marketing platforms.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📂 Dataset

The dataset contains advertising and sales information with features such as:

| Feature | Description |
|----------|-------------|
| TV | Advertising budget spent on TV |
| Radio | Advertising budget spent on Radio |
| Newspaper | Advertising budget spent on Newspapers |
| Sales | Product sales (Target Variable) |

---

## 🔄 Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Explored dataset structure and feature information.

### 2. Data Exploration
- Checked dataset dimensions and data types.
- Analyzed feature distributions.
- Examined relationships between advertising channels and sales.

### 3. Data Preprocessing
- Checked for missing values.
- Prepared features and target variable for training.

### 4. Train-Test Split
- Divided the dataset into:
  - 80% Training Data
  - 20% Testing Data

### 5. Model Building
- Implemented a Linear Regression model.
- Trained the model on the training dataset.

### 6. Model Evaluation
- Predicted sales values on test data.
- Evaluated performance using:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)

### 7. Prediction
- Used the trained model to predict sales for new advertising budgets.

---

## 📊 Model Performance

The model was evaluated using multiple regression metrics:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

These metrics help determine the model's accuracy and prediction capability.

---

## 📈 Example Prediction

**Input:**

```python
new_data = [[230.1, 37.8, 69.2]]
```

Where:

- TV Budget = 230.1
- Radio Budget = 37.8
- Newspaper Budget = 69.2

**Output:**

```text
Predicted Sales: XX.X Units
```

---

## 📁 Project Structure

```text
Sales-Prediction/
│
├── advertising.csv
├── sales_prediction.ipynb
├── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/sales-prediction.git
```

### 2. Navigate to the project directory

```bash
cd sales-prediction
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib scikit-learn
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open and run

```text
sales_prediction.ipynb
```

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data Analysis using Pandas
- Data Visualization
- Feature Selection
- Train-Test Splitting
- Linear Regression
- Model Evaluation Metrics
- Sales Forecasting Techniques
- Predictive Analytics

---

## 👨‍💻 Author

**Kashyap Solanki**

If you found this project useful, feel free to ⭐ the repository and connect with me on LinkedIn.
