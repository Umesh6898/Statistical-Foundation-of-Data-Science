🎓 Analysis of Student Evaluation Dataset
🧭 Purpose of the Study

This analysis focuses on exploring a dataset that captures student evaluations of university faculty members.
Using Python tools such as NumPy, pandas, and Matplotlib, the objective is to uncover trends and insights related to teaching performance and how it's potentially influenced by demographics and professional background—including factors such as tenure, age, gender, and minority status.

📊 Overview of the Dataset

The dataset includes detailed records for each professor, combining both personal attributes and student feedback.

Column	Description
prof	Unique ID assigned to each professor
age	Professor's age in years
gender	Gender identity (Male/Female)
minority	Whether the professor identifies as a visible minority (Yes/No)
tenure	Indicates if the professor holds tenure (Yes/No)
eval	Average rating received from students (scale of 1 to 5)
students	Number of student responses received
beauty	A numerical score based on perceived appearance
division	Course level taught (Lower or Upper division)
🧰 Technologies and Libraries Utilized
Library/Tool	Function
Python (v3.x)	Main programming language for the analysis
pandas	Reading and manipulating tabular data
NumPy	Statistical and numerical operations
Matplotlib	Creating standard plots and visualizations
Seaborn	Producing styled and statistical visualizations
Google Colab	Cloud-based environment for coding and visualization tasks
🧾 Key Findings
1. Tenure and Minority Representation

We examined whether professors who belong to visible minority groups are less likely to be tenured.

Among minority professors, 65.6% hold tenure.

Among non-minority professors, 61.8% are tenured.

🔍 Insight: The difference in tenure rates is marginal, suggesting no significant disparity in tenure status based on minority identity in this dataset.

2. Age Distribution by Tenure

The age profiles of tenured and non-tenured professors were compared:

Tenured Faculty: Average age = 52.3 years, SD ≈ 11.0

Non-Tenured Faculty: Average age = 51.4 years, SD ≈ 11.4

🔍 Insight: As expected, tenured professors tend to be slightly older, reflecting career progression. Age variability is similar across both groups.

3. Age Visualization

To understand the spread of ages, both a histogram and a boxplot were produced.

🔍 Insight: The histogram provided a clearer picture of how professor ages are distributed across the dataset, making it a more effective visualization for this variable.

4. Visualizing Gender Distribution

The gender breakdown among professors was illustrated using bar charts. Both vertical and horizontal bar charts were discussed, with a vertical bar chart used for the final visualization.

🔍 Insight: This approach effectively showed the relative counts of male and female professors, offering a simple visual representation of gender composition.

5. Evaluation Scores for Tenured Faculty

We calculated the median student evaluation score specifically for tenured faculty members.

🔍 Insight: The median rating for tenured professors was found to be 3.25, indicating a moderate level of student satisfaction.
