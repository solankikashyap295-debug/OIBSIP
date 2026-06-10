# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the selling price of used cars using Machine Learning. The model analyzes various car attributes such as manufacturing year, fuel type, transmission type, kilometers driven, and ownership history to estimate the car's market value.

A Linear Regression model is built using Scikit-learn, with data preprocessing handled through Column Transformer and Pipeline for a streamlined machine learning workflow.

---

## 🎯 Objective

To develop a machine learning model that can accurately predict the selling price of a used car based on its features.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

---

## 📂 Dataset

The dataset contains information about used cars with features such as:

| Feature | Description |
|----------|-------------|
| Year | Manufacturing year of the car |
| Present_Price | Current showroom price |
| Driven_kms | Total kilometers driven |
| Fuel_Type | Type of fuel used |
| Selling_type | Dealer or Individual |
| Transmission | Manual or Automatic |
| Owner | Number of previous owners |
| Selling_Price | Target variable |

---

## 🔄 Project Workflow

### 1. Data Loading
- Loaded the dataset using Pandas.
- Examined dataset structure and feature information.

### 2. Data Preprocessing
- Checked for missing values.
- Separated numerical and categorical features.
- Applied StandardScaler to numerical features.
- Applied OneHotEncoder to categorical features.

### 3. Train-Test Split
- Split the dataset into:
  - 80% Training Data
  - 20% Testing Data

### 4. Feature Engineering
- Used ColumnTransformer to handle different preprocessing techniques for numerical and categorical data.
- Created an automated preprocessing workflow.

### 5. Model Building
- Built a Linear Regression model.
- Combined preprocessing and model training using Scikit-learn Pipeline.

### 6. Model Training
- Trained the model on the training dataset.

### 7. Model Evaluation
- Predicted car prices on the test dataset.
- Evaluated performance using:
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

---

## 📊 Model Performance

The model was evaluated using the following metrics:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

These metrics help measure prediction accuracy and model reliability.

---

## 🚘 Example Prediction

**Input Features:**

```python
{
    "Year": 2018,
    "Present_Price": 8.5,
    "Driven_kms": 35000,
    "Fuel_Type": "Petrol",
    "Selling_type": "Dealer",
    "Transmission": "Manual",
    "Owner": 0
}
```

**Output:**

```text
Predicted Selling Price: ₹X.XX Lakhs
```

---

## 📁 Project Structure

```text
Car-Price-Prediction/
│
├── car_data.csv
├── car_price_prediction.ipynb
├── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/car-price-prediction.git
```

### 2. Navigate to the project folder

```bash
cd car-price-prediction
```

### 3. Install dependencies

```bash
pip install pandas numpy scikit-learn
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques
- Feature scaling using StandardScaler
- One-Hot Encoding for categorical variables
- Train-Test Splitting
- ColumnTransformer usage
- Scikit-learn Pipelines
- Linear Regression
- Model Evaluation using R² Score, MAE, and RMSE

---

## 👨‍💻 Author

**Kashyap Solanki**

If you found this project useful, feel free to ⭐ the repository and connect with me on LinkedIn.
