# 🧑‍💼 Employee Survey Data Analysis

This is a data analysis project I did using an employee survey dataset. I used Python and Jupyter Notebook to explore the data and understand more about the employees and their work conditions. This project helped me learn how to clean, understand, and find patterns in data.

## 📁 Dataset Used
The dataset is named `employee_survey.csv` and it includes different columns like:
- Employee ID, Age, Gender, Marital Status
- Job Level, Department, Education Level
- Commute Mode, Workload, Job Satisfaction
- Number of Companies Worked, Team Size, etc.

## 🔧 What I Did
Here are the steps I followed in this project:
- Loaded the dataset using `pandas`
- Checked dataset shape, head, tail, and info
- Found unique values and their counts in each column
- Checked data types of all columns
- Checked for missing values and duplicate rows
- Divided the columns into three types:
  - **Continuous variables**: like Age, Experience, Stress, etc.
  - **Categorical variables**: like Gender, MaritalStatus, Dept, etc.
  - **Count variables**: like NumReports, TeamSize
- Used the IQR method to find **outliers** in the data

## 🔍 What I Found
While analyzing the dataset, I found the following:
- There are **missing values** and **duplicate entries** in the data
- Some columns like `Gender`, `Dept`, `MaritalStatus`, and `JobLevel` have very few unique values
- Many employees come from the same departments and job levels
- `JobSatisfaction` is not the same for everyone – some are very satisfied, some are not
- Some people work overtime, and others don’t (`haveOT`)
- Outliers were found in:
  - `Age`
  - `Experience`
  - `PhysicalActivityHours`
  - `Stress`

## 📚 Libraries Used
I used the following Python libraries:
- `pandas` – to read and work with data
- `numpy` – for numerical operations
- `matplotlib` & `seaborn` – for visualizations
- `scipy` – for statistics like IQR

## 💡 What I Learned
- How to explore a dataset from scratch
- How to find unique values, nulls, and outliers
- How to group variables by type
- Importance of data cleaning before analysis

## 🧪 Future Work
In the next part, I will:
- Make graphs to show patterns visually
- Use heatmaps and correlation analysis
- Try basic machine learning like prediction or classification

## 📌 Note
This project is just for learning and practice purpose. I did this to improve my data analysis skills using real-world-like data.

