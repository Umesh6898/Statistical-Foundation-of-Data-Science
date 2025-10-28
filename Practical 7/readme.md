# 🎓 Teachers Rating Dataset Analysis

### 🧭 Objective

The aim of this practical is to explore relationships and differences within the *Teachers’ Rating Dataset* using regression analysis, ANOVA, and correlation tests.

These experiments help determine how factors such as *gender, **beauty, and **age* influence *teaching evaluation scores* and perceptions. Statistical methods are implemented using Python and the statsmodels library for meaningful interpretation.

### 📊 Dataset Description

The dataset (teachers_rating_data (1).csv) contains data about university professors and their corresponding teaching evaluation ratings. It includes demographic and professional details of instructors.

| Column | Description |
| :--- | :--- |
| *prof* | Professor’s unique identifier |
| *Gender* | Gender of the professor (Male/Female) |
| *Age* | Age of the professor in years |
| *Tenure* | Indicates whether the professor is tenured (Yes/No) |
| *Evaluation* | Teaching evaluation score given by students |
| *Students* | Number of students who rated the professor |
| *Beauty* | Numerical score representing the perceived beauty of the professor |
| *CourseLevel* | Course type — lower or upper division |

### 🧰 Tools & Libraries Used

| Tool/Library | Purpose |
| :--- | :--- |
| *Python (v3.x)* | Programming environment |
| *pandas* | Data manipulation and preprocessing |
| *statsmodels* | Regression, T-test, and ANOVA analysis |
| *scipy* | Statistical hypothesis testing |
| *Google Colab* | Code execution and visualization environment |

### 🧾 Results Summary

Statistical analyses were performed to answer three key questions, using a significance level of p < 0.05.

1.  *Gender & Evaluation (Regression T-test)*
    * *Question:* Does gender affect teaching evaluation rates?
    * *Result:* No. There is *no statistically significant difference* in teaching evaluation ratings between male and female instructors (p = 0.656).

2.  *Age & Beauty (ANOVA)*
    * *Question:* Does the beauty score for instructors differ by age group?
    * *Result:* No. The ANOVA test found that instructors’ beauty scores *do not significantly differ* across age groups (20s, 30s, 40s, 50s) (F(4,116) = 0.96, p = 0.413).

3.  *Beauty & Evaluation (Correlation / Regression)*
    * *Question:* Is teaching evaluation score correlated with beauty score?
    * *Result:* No. Beauty score was *not a significant predictor* of teaching evaluations (p = 0.295). This indicates that, in this dataset, instructors’ beauty scores have no meaningful statistical impact on their evaluation ratings.

### 🏁 Conclusion

This practical provided hands-on experience in:

* Applying OLS (Ordinary Least Squares) regression to interpret coefficients.
* Conducting T-tests and ANOVA for hypothesis testing between groups.
* Exploring correlation (via regression) between continuous variables.

The exercise improved understanding of data-driven hypothesis testing and inferential statistics. In this specific dataset, *none of the tested factors* (gender on evaluation, age on beauty, or beauty on evaluation) showed a statistically significant relationship.
