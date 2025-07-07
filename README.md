# ❤️ Heart Disease Dataset - EDA and Preprocessing

This project contains **Exploratory Data Analysis (EDA)** and **data preprocessing** on a Heart Disease dataset. The primary goal is to understand the factors associated with heart disease and prepare the dataset for machine learning applications.

---

## 📁 Project Structure

```
├── heart.csv               # Original dataset
├── clean_heart.csv         # Cleaned dataset ready for ML
├── heart.ipynb             # Jupyter Notebook with EDA and preprocessing
└── README.md               # Project documentation
```

---

## 📌 Dataset Description

The dataset includes various medical attributes related to heart disease diagnosis.

### Features in `heart.csv` include:
- `Age`: Age of the patient
- `Sex`: Gender
- `ChestPainType`: Type of chest pain
- `RestingBP`: Resting blood pressure
- `Cholesterol`: Serum cholesterol (mg/dl)
- `FastingBS`: Fasting blood sugar > 120 mg/dl
- `RestingECG`: Resting electrocardiographic results
- `MaxHR`: Maximum heart rate achieved
- `ExerciseAngina`: Exercise-induced angina (yes/no)
- `Oldpeak`: ST depression induced by exercise
- `ST_Slope`: Slope of the peak exercise ST segment
- `HeartDisease`: Target variable (0 = No, 1 = Yes)

---

## 🧼 Cleaned Dataset: `clean_heart.csv`

This file contains a machine-learning ready version of the dataset. Preprocessing steps include:
- Encoding categorical features (e.g., `Sex`, `ChestPainType`, `ST_Slope`)
- Handling zero or missing-like values in features like `Cholesterol`
- Chi-Square tests for feature relevance
- Feature transformation (if needed)
- Removed no outliers to preserve original distribution

---

## 📒 Notebook: `heart.ipynb`

The notebook includes:
- 📊 In-depth EDA using Pandas, Matplotlib, and Seaborn
- 🧼 Data preprocessing steps
- 🔍 Chi-Square test of independence for categorical features
- 💾 Export of cleaned dataset as `clean_heart.csv`

---

## 🚀 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/heart-disease-eda.git
   cd heart-disease-eda
   ```

2. **Open the notebook**:
   ```bash
   jupyter notebook heart.ipynb
   ```

3. **Run all cells** to explore and process the dataset.

---

## 📦 Requirements

Install required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ✅ What’s Next?

You can now use `clean_heart.csv` for:
- Classification modeling (e.g., predict presence of heart disease)
- Feature importance analysis
- Model evaluation (e.g., logistic regression, decision trees)

---

## 🤝 Contributions

Feel free to fork the repo and contribute improvements, visualizations, or machine learning models.

---

## 📄 License

This project is open-source and available under the MIT License.
