
# 📈 Titanic Survival Prediction using  — Logistic Regression

This project will help us to predict **survival** of the passengers on Titanic using **Logistic Regression** based on the  based on their passenger data **(ie name, age, gender, socio-economic class, etc)**. The goal of this notebook is to accurately  predict the survival of passenegers while optimizing the number of features used. In addition to achieving high accuracy, this notebook will explore whether similar evaluation metrics can be maintained with a distint feature set.

---

## 📂 Dataset

This dataset consists of a CSV file which comprises of 891 rows and 8 columns. It will result out in sorting of people who were more likely to survive based on the  passenger data (ie name, age, gender, socio-economic class, etc).

## 🔧 Libraries Used

- `pandas` — Data loading and manipulation  
- `numpy` — Numerical operations  
- `matplotlib`, `seaborn` — Data visualization  
- `sklearn` — Machine learning (model, training, evaluation)

---

## 🛠️ Steps Performed

1. **Import Libraries**  
2. **Upload and Read CSV Dataset**
3. **Data Cleaning**  
   - Checked for null values  
4. **Exploratory Data Analysis (EDA)**  
   - Countplot visualization using seaborn  
5. **Train-Test Split**  
   - 75:25 ratio using `train_test_split()`  
6. **Model Creation**  
   - Using `LogisticRegression` from scikit-learn  
7. **Prediction**  
   - Predicted survival for test data  
8. **Evaluation Metrics**
   - Accuracy_score 
   - Confusion_Matrix
9. **Visualization**  
   - Heat Map of **Actual vs Predicted**

---

## 📊 Evaluation Output

```  
Accuracy_score: 79.88826815642458
```

This indicates a good accuracy prediction model.

---

## 📌 Visualization

A Confusion Matrix is generated to show the **Actual vs Predicted** values with a reference bar:

- X-axis → Actual  
- Y-axis → Predicted 

---

## 🙏 Acknowledgement

This project was created under the guidance of [Surekha Kanwar](https://www.linkedin.com/in/surekha-kanwar-81002076/), as part of my machine learning learning journey. I am thankful for her feverish support and knowledge.

---

## 🚀 Run the Code

You can run this project by copying the code into a new notebook and uploading your dataset.

---

## 📬 Contact

For any suggestions or collaborations, feel free to connect on [](https://www.linkedin.com/in/aditya-saraswat-51257b256ar-81002076/), or mail me.
## 📬 Contact

For any suggestions or collaborations, feel free to connect on [](https://www.linkedin.com/in/janshi-singh-2b0b5536a), or mail me.
