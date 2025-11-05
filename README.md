💰 Income Classifier Project
A machine learning solution to predict whether a person's income is above or below 50K using the famous Adult dataset. Built with scikit-learn and pandas, and visualized with seaborn & matplotlib.


🚀 Project Overview
Goal: Predict income category (<50K or ≥50K) based on demographic and work features


Model Used: DecisionTreeClassifier 🌳


Tech Stack: Python 🐍, pandas 🐼, scikit-learn 🤖, matplotlib 📈, seaborn 🌊


🗃️ Dataset
Source: UCI Adult Dataset

Rows: 32,561

Features: 14

Target: income (<50K, ≥50K)


Columns:

👴 age: Age

💼 workclass: Type of job sector

🔢 fnlwgt: Final weight

🎓 education: Education level

🏫 education.num: Education score

💍 marital.status: Marital status

🛠️ occupation: Job title

👨‍👩‍👦 relationship: Family relationship

🌈 race: Race

🚻 sex: Gender

💰 capital.gain: Capital gain

📉 capital.loss: Capital loss

⏰ hours.per.week: Weekly work hours

🌍 native.country: Country of origin

🤑 income: Income class (<50K, ≥50K)


⚙️ Requirements
Python 3.x 🐍

pandas 🐼

numpy 🧮

matplotlib 📈

seaborn 🌊

scikit-learn 🤖


🛠️ Installation & Usage
bash
pip install -r requirements.txt
Place adult dataset.csv in your working directory.

Open and run Income_classifier.ipynb in Jupyter.

Model training, prediction, and evaluation are included!

Results: Accuracy score and confusion matrix 📊


📖 Project Structure
Income_classifier.ipynb — Main notebook

adult dataset.csv — Data file

requirements.txt — Python dependencies


⭐ Results
Accuracy: Shown in notebook output ✅

Confusion Matrix: Visualized for model performance 🟩🟦🟥


💡 Notes
Automatic handling of missing values 🙅‍♀️

Features visualized with charts and graphs 📉

Label encoding for categorical columns 💡

🌈 License
Open-source for education and non-commercial use 🎓

Enjoy building and customizing! If you found this project helpful, give it a ⭐ on GitHub!
