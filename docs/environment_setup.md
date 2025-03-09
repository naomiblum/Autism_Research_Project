# Environment Setup

## 📌 Prerequisites
- Python 3.10+
- Git installed and configured
- Virtual environment (`autism_env`)

## 📌 Installing Required Libraries
Run the following command to install dependencies:
```bash
pip install -r requirements.txt
📌 Setting Up the Repository
bash
Copy
Edit
git clone https://github.com/naomiblum/Autism_Research_Project.git
cd Autism_Research_Project
📌 Virtual Environment
bash
Copy
Edit
python -m venv autism_env
source autism_env/bin/activate  # Mac/Linux
autism_env\Scripts\activate  # Windows

---

## 📜 **4. Data Preprocessing (`data_preprocessing.md`)**

```md
# Data Preprocessing

## 📌 Steps for Cleaning and Preparing the Data
### ✅ 1. Handling Missing Values
- Use **imputation techniques** to replace missing SNP data.
- Consider **removing non-informative features**.

### ✅ 2. Normalization and Feature Scaling
- Apply **MinMax Scaling** for numerical features.
- Normalize categorical genetic markers.

### ✅ 3. Dimensionality Reduction
- Use **PCA** to reduce the number of features.
- Test **Lasso Regression** for feature selection.

---

