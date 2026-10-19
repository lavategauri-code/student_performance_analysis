Student Performance Analysis

In this project I explored a dataset about students lives and school performance. I wanted to see which factors seem to be connected to students final grades. I used Python in a Jupyter notebook.

What I wanted to find out
- Which factors are related to students final grades: study time, absences, or previous class failures?

Data

- Source: Student Performance dataset (math course, student-mat.csv) from the UCI Machine Learning Repository
- What it has: 395 students, one row per student, with details about their life and school, plus their final grade (G3, scored 0 to 20)
- Cleaning: I checked the shape, column types, and missing values. The data was mostly clean and I didn't find any missing values to remove.

What I did
- Loaded the data and checked its structure and summary statistics.
- Made count plots to see how absences, study time, previous failures, and final grades are spread out.
- Grouped students by absences, study time, and previous failures and compared the average final grade for each group.
- Made bar charts and a scatter plot to compare the groups, with the number of students labeled on each one.

What I found
- Absences: Most students have few absences, but a small group has many. The mean (5.71) is higher than the median (4), which shows the data is skewed to the right.
- Study time: Most students study less than 5 hours a week. Students who studied more than 5 hours averaged about 11.3 out of 20, compared with about 10.1 for students who studied less, but there are fewer students in those groups.
- Previous failures: This had the clearest link to grades. Students with no previous failures averaged 11.3 out of 20, compared with 8.1 for one failure and about 6 for two or more.
- Final grades: Most students scored around 10 to 11 out of 20.

Limits
- This shows connections, not causes. A factor being linked to grades doesn't mean it changes them. Some groups have only a few students, so their averages are less reliable. I could only use the variables that are in the dataset.

Files
- student_performance_analysis.ipynb	My notebook with the code, charts, and notes
- student-mat.csv	The dataset

Tools
- Python, pandas, matplotlib, seaborn, Jupyter in VS Code
