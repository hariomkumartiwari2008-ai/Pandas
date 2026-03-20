# Pandas
Introduction
Pandas is an open-source Python library used for data manipulation and analysis. It provides powerful and flexible data structures that make working with structured data fast and easy.
Pandas is widely used in data science, machine learning, and analytics.
🚀 Key Features
Easy Data Handling
Simplifies working with structured data (tables, spreadsheets).
Powerful Data Structures
Provides Series and DataFrame.
Data Cleaning & Transformation
Handle missing values, filtering, reshaping.
Fast Performance
Built on top of NumPy.
Flexible I/O Tools
Supports CSV, Excel, SQL, JSON, etc.
Time Series Support
Ideal for time-based data analysis.
🧠 Core Data Structures
1. Series
One-dimensional labeled array
Similar to a column in a table
Python id="pd1"
Copy code
import pandas as pd

data = pd.Series([10, 20, 30])
print(data)
2. DataFrame
Two-dimensional table (rows & columns)
Most commonly used structure
Python id="pd2"
Copy code
import pandas as pd

data = {
    "Name": ["A", "B", "C"],
    "Marks": [85, 90, 78]
}

df = pd.DataFrame(data)
print(df)
🛠️ Applications of Pandas
Data Cleaning
Data Analysis
Data Visualization (with Matplotlib/Seaborn)
Machine Learning Preprocessing
Financial Data Analysis

🏁 Conclusion
Pandas is an essential library for anyone working with data in Python. Its powerful features and simplicity make it a cornerstone of data analysis, machine learning, and data science workflows.
