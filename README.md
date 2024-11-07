# Data Analysis with Python: Car Dataset Project

In this project, we explore and clean a car dataset using Python and Pandas, performing several data manipulation tasks. This project is ideal for learning key data science and data cleaning techniques in Python.

## Project Overview

This project demonstrates essential data analysis techniques using a car dataset. The project involves tasks like handling missing values, analyzing unique entries, filtering data, removing unwanted records, and applying custom functions to columns. Each step is performed with Python's Pandas library.

### Dataset Description

The dataset contains information about various car models, including attributes like Make, Model, Type, Origin, MSRP, EngineSize, Cylinders, and more. 

---

## Questions and Solutions

### Q1: Find and Fill Null Values
**Objective:** Identify any missing values in the dataset and fill them with the mean for numeric columns, and with "Unknown" for non-numeric columns.

![]()
**Explanation:** I first checked for null values across each column. To handle missing data, I filled numeric columns with their mean values, ensuring continuity in analysis without the skew of missing values. For non-numeric columns, "Unknown" was used to preserve categorical clarity.

### Q2: Count the Types of Car Makes
**Objective:** Determine the number of occurrences for each car manufacturer in the dataset.

![]()
**Explanation:** Using value_counts(), I created a frequency count for each unique car Make. This provided insight into the diversity and distribution of manufacturers in the dataset, which could be useful for brand-focused analysis.

### Q3: Filter Records by Origin
**Objective:** Display records where the car's origin is either "Asia" or "Europe".

![]()
**Explanation:** By filtering the Origin column, I isolated entries for cars originating from Asia and Europe. This selection allows for focused analysis on these regions without the influence of data from other origins.

### Q4: Remove Records Based on Weight
**Objective:** Remove records where the car's weight exceeds 4000.

![]()
**Explanation:** To reduce the effect of outliers on my analysis, I removed entries where the weight exceeded 4000. This step provided a more normalized dataset for further calculations, particularly when analyzing fuel efficiency and performance metrics.

### Q5: Adjust City MPG Values
**Objective:** Increase all values in the MPG_City column by 3.

![]()


### Conclusion
This project provided hands-on experience in data cleaning, transformation, and basic analysis with Python and Pandas. Each step allowed me to tackle a real-world data task, building skills that are directly applicable in data science and analysis roles.

