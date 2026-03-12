
# COVID-19 Data Handling and Analysis

This repository contains a Jupyter notebook for analyzing COVID-19 data, focusing on Indian states and global trends. The notebook demonstrates data cleaning, filtering, and exploratory data analysis techniques using Python.

## 📊 Dataset Overview

The analysis uses two main datasets:
1. **Indian States Data**: State-wise COVID-19 statistics including confirmed cases, deaths, and recoveries
2. **Global COVID-19 Data**: World-wide pandemic data from Our World in Data (OWID)

## 🛠️ Technologies Used

- Python 3
- Pandas for data manipulation
- NumPy for numerical operations
- Jupyter Notebook

## 📁 Project Structure

The notebook is organized into two main sections:

### 1. Indian State-wise Analysis
- Loading and exploring state-level COVID-19 data
- Data cleaning and feature selection
- Focused analysis on Kerala's COVID-19 trends
- Handling zero values in early pandemic data

### 2. Global COVID-19 Analysis
- Loading worldwide COVID-19 dataset
- Filtering data for India-specific analysis
- Temporal analysis from January 2020 to July 2021
- Statistical summary of new cases in India

## 🔍 Key Analysis Performed

- Data cleaning and column optimization
- Statistical summaries (mean, std, min, max, quartiles)
- Time series filtering for India
- Handling missing values and zero entries
- Data quality assessment

## 📈 Sample Insights

- The Kerala dataset shows many zero values in early records, reflecting the initial stages of the pandemic
- India's COVID-19 data spans from January 30, 2020, to July 4, 2021
- Statistical analysis reveals significant variation in daily new cases (0 to 414,188 cases)

## 🚀 How to Use

1. Clone this repository
2. Install required dependencies:
   ```bash
   pip install pandas numpy jupyter
   ```
3. Update the file paths in the notebook to point to your local data files
4. Run the notebook cells sequentially

## 📁 Data Files Required

- `complete corona data.csv` - Indian states COVID-19 data
- `owid-covid-data.csv` - Global COVID-19 data from Our World in Data

## ⚠️ Note

The notebook includes absolute file paths that need to be updated to match your local system configuration. Example:
```python
df = pd.read_csv('your_path_here/complete corona data.csv')
```

## 📊 Key Findings

- Initial pandemic data contains numerous zero values due to limited spread
- Indian data shows progression from single cases to large daily increases
- The analysis provides statistical overview of pandemic progression in India

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements or additional analyses.

## 📝 License

This project is open-source and available for educational and research purposes.

## 👤 Author

**Sumit Nayek**

---
