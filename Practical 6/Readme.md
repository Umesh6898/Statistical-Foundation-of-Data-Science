🎓 Teachers Rating Dataset Analysis
🧭 Objective

The objective of this analysis is to explore a dataset of university instructors’ teaching evaluations using Python libraries such as NumPy, pandas, and SciPy.
The goal is to perform statistical tests, evaluate relationships among variables, and interpret whether characteristics such as gender, tenure, age, and beauty scores influence teaching evaluation outcomes.

📊 Dataset Description

The dataset provides information about university instructors and their teaching evaluation ratings.
It includes the following variables: Professor Name, Gender, Tenure Status, Beauty Score, Teaching Evaluation Rating, Number of Students, Age, and Course Division (Lower or Upper).

Each row represents an instructor’s course evaluation. Some columns, such as Beauty and Students, contain outliers. The Rating variable represents the teaching evaluation score on a scale from 1 to 5.

🧩 Note: This dataset is synthetic and intended for statistical analysis practice.

⚙️ Tools Used

Python 3.x

NumPy

pandas

SciPy

Jupyter Notebook / Google Colab

🧪 Statistical Results & Interpretation
1️⃣ Gender and Evaluation (Independent T-Test)

T-statistic: -0.4462

P-value: 0.6563

The negative T-statistic shows that the average Evaluation score for male professors is slightly lower than that for female professors.
However, since the p-value is greater than 0.05, this difference is not statistically significant.

Interpretation: Gender does not significantly affect teaching evaluation ratings. Any difference in scores is likely due to random variation.

2️⃣ Tenure and Evaluation (Independent T-Test)

T-statistic: -1.0848

P-value: 0.2802

The negative T-statistic suggests that tenured professors have slightly lower evaluation scores on average compared to non-tenured professors.
But again, the p-value is greater than 0.05, meaning the result is not statistically significant.

Interpretation: There is no significant difference in teaching evaluation scores between tenured and non-tenured professors.

3️⃣ Correlation Between Beauty and Evaluation

Correlation Coefficient: 0.1043

P-value: 0.2567

The correlation coefficient indicates a very weak positive relationship between Beauty and Evaluation.
However, the p-value exceeds the 0.05 threshold, meaning this correlation is not statistically significant.

Interpretation: There is no meaningful correlation between beauty and teaching evaluation scores.
While beauty scores slightly increase with evaluation scores, the effect is too weak to be considered real.

🧩 Conclusion

All statistical analyses indicate no significant relationships between the studied variables.
Gender and tenure status do not meaningfully affect evaluation scores, and beauty has only a weak, non-significant correlation with teaching evaluations.

These findings suggest that, in this dataset, factors such as appearance, gender, and tenure do not substantially influence how professors are evaluated by students.
Any observed differences are likely due to random variation rather than true underlying effects.
