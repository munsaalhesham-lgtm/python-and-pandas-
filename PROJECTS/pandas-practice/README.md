# Pandas Practice Project

A hands-on learning project for mastering Python's pandas library. This repository contains practical examples and exercises for working with data manipulation, analysis, and visualization using pandas.

## Overview

This project is designed to help you learn and practice essential pandas skills including:
- Creating and manipulating DataFrames
- Data cleaning and preparation
- Data aggregation and grouping
- Merging and joining datasets
- Data visualization and analysis

## Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/pandas-practice.git
cd pandas-practice
```

### 2. Install Dependencies

Install the required packages using the requirements file:

```bash
pip install -r requirements.txt
```

This will install:
- **pandas** (>= 1.3.0) - Data manipulation and analysis
- **numpy** (>= 1.21.0) - Numerical computing

## Quick Start

Run the main example script:

```bash
python main.py
```

This will execute a basic example demonstrating how to create and display a pandas DataFrame.

## Project Structure

```
pandas-practice/
├── main.py              # Main example script
├── README.md            # This file
├── requirements.txt     # Python dependencies
└── pandas-practice.code-workspace  # VS Code workspace configuration
```

## Topics Covered

### Core Concepts
- **DataFrames** - Working with tabular data structures
- **Series** - Understanding one-dimensional labeled arrays
- **Data Types** - Managing and converting data types

### Data Manipulation
- **Data Cleaning** - Handling missing values, duplicates, and outliers
- **Data Selection** - Filtering, indexing, and slicing data
- **Data Transformation** - Applying functions and creating derived columns

### Data Analysis
- **Grouping and Aggregation** - Summarizing data by groups
- **Merging and Joining** - Combining multiple datasets
- **Pivot Tables** - Reshaping and cross-tabulating data

### Data Visualization
- Creating plots and charts (with matplotlib/seaborn)
- Exploratory Data Analysis (EDA) techniques

## Usage Examples

### Creating a DataFrame

```python
import pandas as pd

data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [25, 30, 35],
    'City': ['New York', 'London', 'Paris']
}

df = pd.DataFrame(data)
print(df)
```

### Basic Operations

```python
# Display first few rows
df.head()

# Get basic statistics
df.describe()

# Filter data
filtered = df[df['Age'] > 26]

# Group and aggregate
grouped = df.groupby('City').agg({'Age': 'mean'})
```

## Resources

- [Pandas Official Documentation](https://pandas.pydata.org/docs/)
- [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- [Real Python Pandas Tutorial](https://realpython.com/learning-paths/pandas-data-science/)

## Getting Help

If you encounter any issues:
1. Check the [pandas documentation](https://pandas.pydata.org/)
2. Search for solutions on [Stack Overflow](https://stackoverflow.com/questions/tagged/pandas)
3. Refer to the examples in `main.py`

## Contributing

Feel free to:
- Add more examples and exercises
- Improve existing code
- Add new data processing techniques
- Fix bugs or issues
- Update documentation

## License

This project is open source and available under the MIT License.

## Author

Created as a learning resource for pandas practice.

---

**Happy Learning!** Start with `main.py` and expand with your own examples.
