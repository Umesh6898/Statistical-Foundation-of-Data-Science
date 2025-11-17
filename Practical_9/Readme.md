🌸 Iris Dataset — KNN Classification Analysis

🧭 Objective

The aim of this practical is to apply the K-Nearest Neighbors (KNN) algorithm to the Iris dataset to classify different flower species.

This experiment covers:

Exploratory Data Analysis (EDA)

Feature Normalization

Model Training

Error Rate Comparison

Choosing the Best K

Model Assessment & Visualization

This practical builds understanding of how distance-based classification works in machine learning.

📊 Dataset Description

The Iris dataset includes measurements of 150 iris flowers from three species.

📁 Columns Description

Column	Description

sepal length (cm)	Length of the sepal

sepal width (cm)	Width of the sepal

petal length (cm)	Length of the petal

petal width (cm)	Width of the petal

species	Target class: Setosa, Versicolor, Virginica

🧰 Tools & Libraries Used

Tool / Library	Purpose

Python (3.x)	Programming language

pandas	Data handling & EDA

NumPy	Mathematical operations

scikit-learn	KNN model, scaling, evaluation metrics

Matplotlib	Visualizations

Jupyter Notebook / Google Colab	Running the analysis

🧪 Procedures & Results

1️⃣ Exploratory Data Analysis (EDA)

Conducted using:

head() → Initial look at the dataset

describe() → Statistical summary

groupby() → Species-level comparison

This helps reveal feature patterns and differences among species.

2️⃣ Feature Scaling

StandardScaler was used to standardize the numerical features.

Scaling is essential for KNN since it relies on distance calculations.

3️⃣ Train-Test Split & KNN Model Training

Split ratio → 70% training, 30% testing

Initial KNN model built using K = 5

4️⃣ Confusion Matrix & Accuracy Score

After generating predictions:

The confusion matrix displays classification performance

The accuracy score typically exceeds 95%, showing strong results

5️⃣ Classification Report

Includes:

Precision

Recall

F1-score

All three species show strong classification metrics due to clear separation in the dataset.

6️⃣ Error Rate Comparison for K = 1 to 20

K values from 1 to 20 were tested to examine how the error rate changes.

This helps in identifying the most reliable K value.

7️⃣ Plot: Error Rate vs K Values

The line plot shows:

Error rate variations

High-performing K values

Overfitting at very small K values

More stable performance at higher K values

8️⃣ Determining the Best K

The optimal K is the one with the lowest error rate.
For the Iris dataset, it typically falls between K = 3 and 7.

9️⃣ Visualization of Results (PCA)

Using PCA with 2 components, a scatter plot was created showing:

Data points colored by species

Clear separation among Setosa, Versicolor, and Virginica

📈 Summary of Findings

Step	Purpose	Result

EDA	Explore the dataset	Clear species-level differences

Scaling	Normalize features	Crucial for KNN

Model Training	Build the classifier	K=5 gives strong performance

Confusion Matrix	Evaluate results	Very high accuracy

Error Analysis	Identify best K	Optimal K around 3–7

PCA Plot	Visualize classes	Clusters are easily distinguishable

🏁 Conclusion

This practical provided hands-on experience with:

✔ Building a KNN classifier

✔ Understanding the role of scaling

✔ Evaluating model performance metrics

✔ Experimenting with different K values

✔ Visualizing high-dimensional data through PCA

Key Insights

KNN works exceptionally well on the Iris dataset because of the distinct separation among species.

Choosing the right K helps balance accuracy and generalization.

PCA-based visualizations provide valuable intuition about dataset structure.
