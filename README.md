📈Titanic Survival Prediction using — Logistic Regression
This project will help us to predict survival of the passengers on Titanic using Logistic Regression  based on their passenger data (ie name, age, gender, socio-economic class, etc).. The goal of this notebook is to accurately predict the survival of passenegers while optimizing the number of features used. In addition to achieving high accuracy, this notebook will explore whether similar evaluation metrics can be maintained with a distint feature set.

📂 Dataset


These symptoms are mapped to 42 diseases you can classify these set of symptoms too.

🔧 Libraries Used
pandas — Data loading and manipulation
numpy — Numerical operations
matplotlib, seaborn — Data visualization
sklearn — Machine learning (model, training, evaluation)
🛠️ Steps Performed
Import Libraries
Upload and Read CSV Dataset
Data Cleaning
Checked for null values
Exploratory Data Analysis (EDA)
Countplot visualization using seaborn
Train-Test Split
75:25 ratio using train_test_split()
Model Creation
Using RandomForestClassifier from scikit-learn
Prediction
Predicted prognosis for test data
Evaluation Metrics
F1_score
Accuracy_score
Precision_score
Recall_score
Confusion_Matrix
Visualization
Count plot of Symptoms vs Prognosis
📊 Evaluation Output
Accuracy_score: 90.9090909090909%
F1_score : 0.8070175438596491%
precision_score : 0.95%
recall_score : 0.75%
This indicates a good accuracy prediction model.

📌 Visualization
A Count plot is generated to show the Symptoms vs Prognosis values with a reference bar:

X-axis → Symptoms Count
Y-axis → Prognosis
🙏 Acknowledgement
This project was created under the guidance of Surekha Kanwar, as part of my machine learning learning journey. I am thankful for her feverish support and knowledge.

🚀 Run the Code
You can run this project by copying the code into a new notebook and uploading your dataset.

📬 Contact
For any suggestions or collaborations, feel free to connect on , or mail me.
