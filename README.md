# Dataset — Student Performance (UCI)

Source: UCI Machine Learning Repository — Student Performance Data Set
Link: https://archive.ics.uci.edu/dataset/320/student+performance
Citation: Cortez, P., & Silva, A. (2008). Using Data Mining to Predict Secondary School Student Performance.

## Files

- **student-mat.csv** — original Mathematics course dataset (395 records, 33 attributes, semicolon-separated)
- **student-por.csv** — original Portuguese course dataset (649 records, 33 attributes, semicolon-separated)
- **student_performance_combined.csv** — the two files merged (1,044 records, 34 columns — includes a `subject` column marking math/portuguese), comma-separated. This is the exact dataset used throughout the notebook for EDA, feature engineering, and modeling.

## Note

The notebook (`student_performance_analysis.ipynb`) is self-contained and does not require these files to run — it has the same data embedded internally as base64, so it works standalone on any machine. These CSV files are provided separately here to satisfy the submission requirement of including a raw dataset alongside the source code.
