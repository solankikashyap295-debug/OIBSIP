# 🌸 Iris Flower Classification using Machine Learning

## 📌 Project Overview
This project uses the famous Iris dataset to classify iris flowers into three species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

The model is built using Python, Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn. A Random Forest Classifier is trained on flower measurements to predict the species of a flower.

---

## 🎯 Objective
To build a machine learning model that can accurately classify iris flowers based on:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset

The Iris dataset contains 150 flower samples with the following features:

| Feature | Description |
|----------|-------------|
| SepalLengthCm | Length of sepal |
| SepalWidthCm | Width of sepal |
| PetalLengthCm | Length of petal |
| PetalWidthCm | Width of petal |
| Species | Flower species |

---

## 🔄 Project Workflow

### 1. Data Loading
- Loaded the dataset using Pandas.
- Examined dataset structure and dimensions.

### 2. Data Preprocessing
- Checked for missing values.
- Removed the unnecessary Id column.
- Encoded species labels using LabelEncoder.

### 3. Exploratory Data Analysis (EDA)
- Generated statistical summaries.
- Visualized relationships between features using Seaborn Pairplots.

### 4. Train-Test Split
- Split dataset into:
  - 80% Training Data
  - 20% Testing Data

### 5. Model Building
- Used Random Forest Classifier with 100 estimators.
- Trained the model on the training dataset.

### 6. Model Evaluation
- Calculated accuracy score.
- Generated a classification report.

### 7. Prediction
- Predicted the species of a new flower sample based on input measurements.

---

## 📊 Model Performance

The Random Forest Classifier achieved excellent classification accuracy on the test dataset.

Evaluation metrics include:
- Accuracy Score
- Precision
- Recall
- F1-Score

---

## 🌼 Example Prediction

**Input:**

```python
new_flower = [[5.1, 3.5, 1.4, 0.2]]
```

**Output:**

```text
Predicted Species: Iris-setosa
```

---

## 📁 Project Structure

```text
Iris-Flower-Classification/
│
├── Iris.csv
├── iris classification.ipynb
├── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/iris-flower-classification.git
```

### 2. Navigate to the project folder

```bash
cd iris-flower-classification
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques
- Exploratory Data Analysis (EDA)
- Label Encoding
- Train-Test Splitting
- Random Forest Classification
- Model Evaluation and Prediction
- Data Visualization using Seaborn and Matplotlib

---

## 👨‍💻 Author

**Kashyap Solanki**

If you found this project useful, feel free to ⭐ the repository and connect with me on LinkedIn.
