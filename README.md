# Statistical-Foundation-of-Data-Science



# Statistical-Foundation-of-Data-Sciences


# Synthetic Data Exercises (Colab / Jupyter Notebook)


> *Instruction summary*
>
> - Use *Google Colab* or *Jupyter Notebook*.
> - Create a synthetic dataset containing some NaN values. Set random seed to *42* at the top.
> - Solve four problems (mean/median/weighted mean; z-score outliers; age bins stats; array ops + linear algebra).

---

## How to run

1. Open Google Colab or a new Jupyter notebook.
2. Follow the steps described in each problem.
3. Execute cells top-to-bottom.

---

## Problems Overview

### Dataset Creation
- Make a DataFrame with columns: id, age, income, score.
- Insert some NaN values in age, income, and score.
- Keep the random seed fixed at *42*.

---

### Problem 1 — Mean, Median, Age‑Weighted Mean
- Compute:
  - Mean of income
  - Median of income
  - Age‑weighted mean of income (handle `NaN`s).
- Add a note on when weighted mean is preferable.

---

### Problem 2 — Z‑Score Standardization & Outliers
- Standardize income using z‑score.
- Mark rows where |z| > 3 as outliers.
- Handle `NaN`s correctly (do not drop entire rows).

---

### Problem 3 — Age Bins & Statistics
- Create age bins: [18‑25), [25‑35), [35‑45), [45‑60).
- For each bin compute:
  - Count of observations
  - Mean income
  - Median score
- Present results as a tidy table sorted by bin.

---

### Problem 4 — Array Operations & Linear Algebra
- Make an array (not 1‑D).
- Show:
  - Shape, size, transpose, flatten.
  - Negative indexing and a captured slicing error.
  - Broadcasting and dot product.
  - Determinant and inverse (check for singular matrix).

---

## Final Notes
- Avoid dropping rows wholesale when handling missing data.
- Use .dropna(subset=[...]) only when specific columns are required.
- Keep np.random.seed(42) for reproducibility.
- Document any special handling of weights or missing values.
