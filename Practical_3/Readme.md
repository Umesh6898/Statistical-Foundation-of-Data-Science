🎓 Teacher Evaluation Dataset Analysis – Practical 3
🧭 Objective

This exercise extends the exploration of the Teacher Evaluation Dataset introduced in Practical 2.
The aim is to carry out data cleaning, duplicate detection, and visualization to better understand how instructors’ age, division, gender, and evaluation scores relate to one another.

📊 Dataset Overview

The dataset includes details about university faculty members and their teaching performance evaluations.

Column	Description
Prof	Instructor’s name (may repeat for professors teaching multiple classes)
Gender	Instructor’s gender — Male or Female
Tenure	Tenure status — Yes or No
Beauty	Attractiveness score of the instructor (contains outliers)
Rating	Student evaluation score ranging from 1 to 5
Students	Total students enrolled per class (one extreme case with 300 students)
Age	Age of the instructor
Division	Course category — “Lower” or “Upper” Division
⚙ Tools Utilized

Python 3.x

NumPy

pandas

Matplotlib

Jupyter Notebook / Google Colab

🧾 Summary

Some instructors appear multiple times since they teach more than one course.
Average age shows minor variation when only unique faculty members are considered.
Lower-division classes tend to have marginally higher teaching evaluations.
No significant correlation is detected between age and evaluation ratings.
Gender and tenure visualizations reveal small differences but no major evidence of bias.
