# 🗞️ Real vs Fake News Classifier using Decision Trees

This project is part of my **machine learning practice journey**, where I explored how to classify news articles as **Real** or **Fake** using a `DecisionTreeClassifier`. The dataset included **text**, **categorical**, **numerical**, and **date-based** features — making it a great opportunity to practice real-world preprocessing and model tuning.

---

## 📁 Dataset

The dataset contains two CSV files:
- `True.csv` – contains real news articles
- `Fake.csv` – contains fake news articles

Each file includes:
- `title`
- `text`
- `subject`
- `date`

---

## 🧠 What I Did

✅ Preprocessed the data:
- Combined both CSVs with proper labels (`real` vs `fake`)
- Handled missing values
- Extracted new features from `date` (month, year, day of the week)
- Applied TF-IDF vectorization to `title` and `text`
- Used `OneHotEncoding` for categorical features
- Standardized numerical features

✅ Built a pipeline using `ColumnTransformer` for:
- Text processing  
- Categorical encoding  
- Feature scaling  
- Handling missing values with `SimpleImputer`

✅ Trained a `DecisionTreeClassifier` with parameters like `max_depth` and `min_samples_split` to prevent overfitting

✅ Evaluated the model:
- Confusion Matrix
- Accuracy, Precision, Recall
- Tested with new custom inputs

---

## ⚙️ Tech Stack

- Python 🐍  
- Pandas & NumPy  
- Scikit-learn (`DecisionTreeClassifier`, `ColumnTransformer`, `TF-IDF`, etc.)  
- Matplotlib & Seaborn for visualizations

---

## 📊 Results

- Model achieved **perfect recall (1.0)** on the test set  
- Confusion Matrix:
[[4684 0]
[ 0 4296]]
- Also tested with new custom inputs, and it predicted accurately

---

## 💡 What I Learned

- How preprocessing can make or break your model  
- Working with **mixed-type features** (text, category, date, numbers)  
- Importance of building clean ML pipelines  
- Identifying overfitting and handling it with regularization  
- How *real-world* projects are never as “clean” as tutorial datasets 😅

---

### 📫 How to Reach Me
Let’s connect, collab, or just vibe over tech and tea 🍵✨
- **Instagram**: [ai_enthusiast86](https://www.instagram.com/ai_enthusiast86)
- **LinkedIn**: [Muskan Tariq](https://www.linkedin.com/in/muskan-tariq-095a50282)
- **Email:** [Muskan Tariq](muskantariq2003@gmail.com)

-----
