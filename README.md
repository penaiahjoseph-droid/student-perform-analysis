
# Students-Performance-Analysis

## Dataset
**Synthetic Dataset** generated using Python libraries.

---

## Objectives

1. Generate a dataset of students using Python libraries such as NumPy, Pandas, and Faker.
2. Analyze student performance by calculating:
   - Total Marks
   - Average Marks
   - Grades
3. Apply descriptive statistics:
   - Mean
   - Median
   - Mode
   - Standard Deviation
4. Classify students into grades (A, B, C, Fail).
5. Identify top-performing and low-performing students.
6. Perform group-wise analysis based on:
   - Department
   - Gender
   - Year
7. Analyze relationships between variables such as Attendance and Average Marks using correlation.
8. Visualize data using:
   - Bar Charts
   - Histograms
   - Scatter Plots
9. Understand patterns and trends in student performance.
10. Improve data analysis skills using Python libraries.

---

## Project Highlights

### Data Preprocessing
- Generated student data using NumPy, Pandas, and Faker.
- Cleaned and structured the dataset.
- Created new features such as Total Marks and Average Marks.
- Converted raw data into a usable format for analysis.
- Ensured data consistency and quality.

### Exploratory Data Analysis (EDA)
- Calculated statistical measures:
  - Mean
  - Median
  - Mode
  - Standard Deviation
- Identified performance patterns among students.
- Compared performance across:
  - Departments
  - Gender
  - Academic Year
- Analyzed the relationship between Attendance and Average Marks.
- Detected trends and variations in the dataset.

### Machine Learning Concept
- Applied a grade classification system.
- Categorized students into:
  - A Grade
  - B Grade
  - C Grade
  - Fail
- Can be extended using machine learning algorithms such as:
  - Logistic Regression
  - Decision Tree
- Useful for predicting student performance.

### Visualization
Created visualizations using Matplotlib:

- Bar Chart → Department-wise performance
- Histogram → Distribution of marks
- Scatter Plot → Attendance vs Average Marks

Example:

```python
plt.scatter(df["Attendance"], df["Average"])
plt.show()
```

These visualizations help identify trends and patterns easily.

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Faker

---

## Results

The project was successfully completed using Python. A synthetic student dataset was generated and analyzed to understand student performance.

### Key Findings
- Most students achieved average scores.
- A small number of students earned high grades.
- Some students were classified as Fail.
- The grading system clearly categorized student performance.
- Statistical analysis indicated moderate overall performance.
- Comparisons across departments, gender, and year showed only minor differences.
- Students with higher attendance generally achieved better marks.
- Visualizations helped reveal important patterns and trends.

Overall, this project enhanced understanding of student performance analysis and improved practical data analysis skills using Python.

---

## Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from faker import Faker
```
