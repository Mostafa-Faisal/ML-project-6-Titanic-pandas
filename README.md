# ML Project 6: Titanic Data Analysis with Pandas

A comprehensive data analysis project exploring the famous Titanic dataset using Python pandas library. This project demonstrates essential data science skills including data cleaning, exploratory data analysis, and basic visualization.

## 📊 Project Overview

This project analyzes the Titanic passenger dataset to understand survival patterns and perform data manipulation tasks using pandas. The analysis includes data cleaning, handling missing values, and extracting meaningful insights from the tragic maritime disaster.

## 🚢 Dataset Information

The Titanic dataset contains information about passengers aboard the RMS Titanic, including:
- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Passenger name
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas**: For data manipulation and analysis
- **NumPy**: For numerical operations
- **Matplotlib**: For data visualization

## 📁 Project Structure

```
ML-project-6-Titanic-pandas/
├── README.md                    # Project documentation
├── Task1_PandasTitanic.ipynb   # Main Jupyter notebook with analysis
├── Titanic-Dataset.csv         # Dataset file
└── .git/                       # Git repository files
```

## 🔍 Analysis Features

### 1. Data Loading and Exploration
- Loading the Titanic dataset using pandas
- Displaying first few rows and basic information
- Getting summary statistics for numerical columns

### 2. Data Quality Assessment
- Identifying missing values in each column
- Checking for duplicate records
- Understanding data types and structure

### 3. Data Cleaning
- Handling missing values in the 'Age' column using median imputation
- Managing missing 'Cabin' data through column removal
- Removing duplicate entries

### 4. Exploratory Data Analysis
- Survival rate analysis
- Age comparison between survivors and non-survivors
- Statistical summaries grouped by survival status

### 5. Basic Visualization
- Bar plots showing survival counts
- Visual representation of key findings

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib jupyter
```

### Running the Analysis
1. Clone this repository:
   ```bash
   git clone https://github.com/Mostafa-Faisal/ML-project-6-Titanic-pandas.git
   cd ML-project-6-Titanic-pandas
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Task1_PandasTitanic.ipynb
   ```

3. Run all cells to execute the complete analysis

## 📈 Key Insights

The analysis reveals important patterns in the Titanic disaster:
- Survival rates across different passenger classes
- Age distribution impact on survival chances
- Gender-based survival statistics
- Missing data patterns and their implications

## 🎯 Learning Objectives

This project demonstrates proficiency in:
- **Data Import**: Loading CSV files with pandas
- **Data Exploration**: Using `.head()`, `.info()`, `.describe()` methods
- **Data Cleaning**: Handling missing values and duplicates
- **Data Analysis**: Grouping and aggregating data
- **Data Visualization**: Creating basic plots with matplotlib
- **Statistical Analysis**: Computing means, medians, and value counts

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements or additional analysis techniques.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

**Mostafa Faisal**
- GitHub: [@Mostafa-Faisal](https://github.com/Mostafa-Faisal)

---

*This project is part of a Machine Learning internship series focusing on practical data science skills.*