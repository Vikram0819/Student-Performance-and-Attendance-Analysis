# Student-Performance-and-Attendance-Analysis

This mini project analyzes student marks and attendance data using Python to derive meaningful academic insights. It covers data cleaning, transformation, performance classification, and rich visualizations to help stakeholders understand patterns and take informed actions.

---

## 📁 Dataset

The dataset is an Excel file with two sheets:

- **Marks** – Student scores in Mini Tests, Live Test, and Assignment  
- **Attendance** – Attendance records for 5 days marked as 'Y' (Yes) or 'N' (No)

---

## 🔧 Technologies & Libraries Used

- **Python** (Jupyter Notebook)
- **Pandas** – for data manipulation
- **Matplotlib** – for visualizations
- **Seaborn** – for advanced charting
- **Microsoft Excel** – as the raw data source

---

##  Features & Analysis

###  Data Preparation

- Loaded and merged Excel data from two sheets
- Cleaned inconsistent student names
- Converted attendance values to numeric
- Handled missing values gracefully

###  Data Transformation

- Calculated total and percentage marks
- Derived attendance percentage
- Computed weighted percentage using:
  - Attendance (40%)
  - Mini Test 1 (10%)
  - Mini Test 2 (10%)
  - Live Test (20%)
  - Assignment (20%)
- Classified students into:
  - Excellent (≥ 85%)
  - Good (71–84%)
  - Average (50–70%)
  - Needs Improvement (< 50%)

###  Analysis Performed

- Identified students with attendance < 75% but weighted % > 50%
- Highlighted top 3 students by percentage marks
- Correlation analysis between attendance and academic scores

###  Visualizations

- Bar chart of top 5 students by weighted percentage
- Pie chart of student performance distribution
- Box plots for each test/assignment to detect outliers
- Bar chart of students with attendance < 50%
- Scatter plot showing attendance vs weighted performance

---

##  Author

**Vikram Rana Singh**  
PGDM Student | Data Science Enthusiast  
[LinkedIn]([https://www.linkedin.com/](https://www.linkedin.com/in/vikram-rana-singh-60273019b/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BQosYN%2BwqRLyx9m%2BiTkmT4w%3D%3D)) | [GitHub]([https://github.com/](https://github.com/Vikram0819))

---

##  License

This project is licensed under the MIT License – feel free to reuse and modify.


