## Task 2 – Exploratory Data Analysis (EDA)

### Objectives
- Visualize relationships between features.
- Identify correlations and distributions.
- Summarize key insights for predictive modeling.

### Steps
1. Generated a **correlation heatmap** for all features.
2. Created **pairplots** for RM, LSTAT, MEDV.
3. Plotted **distributions** for MEDV, RM, LSTAT.

### Visualizations
- `correlation_heatmap.png`
- `pairplot_rm_lstat_medv.png`
- `dist_medv.png`
- `dist_rm.png`
- `dist_lstat.png`

### Insights
- **RM ↗ MEDV:** Strong positive correlation → More rooms → Higher house value.
- **LSTAT ↘ MEDV:** Strong negative correlation → Higher % of lower status population → Lower house value.
- **PTRATIO ↘ MEDV:** Negative correlation → Higher pupil-teacher ratio → Lower house value.
- MEDV distribution shows a cap at 50, indicating a possible limit in the dataset.

### Files
- `Task2_EDA.ipynb` → Notebook with code and visualizations
- `README.md` → Documentation updated with Task 2

