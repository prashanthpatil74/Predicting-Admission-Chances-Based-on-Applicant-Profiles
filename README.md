# Predicting Admission Chances Based on Applicant Profiles

This project implements a machine learning pipeline to predict the **probability of admission to UCLA** for prospective graduate students. Using key applicant features such as GRE scores, TOEFL scores, university rating, Statement of Purpose (SOP), Letter of Recommendation (LOR), CGPA, and research experience, the model estimates admission chances.

---

## Project Overview

Graduate school admissions involve multiple factors, and predicting admission chances helps applicants understand their prospects better. This project analyzes historical admission data to UCLA and builds predictive models.

Key components include:

- Data exploration and cleaning
- Feature engineering and visualization
- Model selection using GridSearchCV
- Model training and evaluation
- Admission probability prediction for new applicants

---

## Dataset Description

| Feature            | Description                           |
|--------------------|-------------------------------------|
| Serial No.         | Unique record identifier             |
| GRE Score          | Graduate Record Examination score (out of 340) |
| TOEFL Score        | Test of English as a Foreign Language score (out of 120) |
| University Rating  | University rating (1 to 5)           |
| SOP                | Statement of Purpose strength (1-5) |
| LOR                | Letter of Recommendation strength (1-5) |
| CGPA               | Undergraduate GPA (out of 10)       |
| Research           | Research experience (0 = No, 1 = Yes) |
| Chance of Admit    | Probability of admission (0 to 1)   |

---

## How It Works

1. **Load and Explore Data**: Understand dataset shape, features, and distributions.
2. **Clean and Prepare Data**: Drop irrelevant columns, handle missing/zero values.
3. **Visualize Features**: Plot histograms to observe distributions.
4. **Build Models**: Use classification algorithms (Logistic Regression, SVM, Random Forest, etc.) with hyperparameter tuning via GridSearchCV.
5. **Evaluate Models**: Use cross-validation for accuracy.
6. **Predict Admission Chances**: Output admission probabilities for new applicant profiles.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
