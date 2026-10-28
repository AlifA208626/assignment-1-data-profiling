
# Assignment 1: Data Profiling and Exploratory Data Analysis (EDA)

## 1. Project Overview

This project focuses on profiling a food delivery dataset to identify data quality issues before conducting further analysis. The main objective is to examine missing values, potential outliers, duplicate records, invalid values, data types, and potential privacy and bias risks.

The findings are used to determine appropriate ways to handle data quality issues and assess whether the dataset is suitable for the selected scenario.

## 2. Dataset

The dataset used in this project is the Zomato Dataset, stored in CSV format.

The dataset contains information related to food delivery, including:
- Delivery personnel information
- Restaurant and delivery locations
- Order dates and times
- Weather conditions and road traffic density
- Vehicle conditions and types
- Delivery duration

**Dataset source:** (https://www.kaggle.com/datasets/saurabhbadole/zomato-delivery-operations-analytics-dataset)

The dataset file is stored in the `data/` directory.

## 3. Project Structure

```text
assignment-1-data-profiling/
├── data/
│   └── Zomato Dataset.csv
├── assignment1_eda.ipynb
└── README.md
```

## 4. Requirements

The project uses Python and the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## 5. How to Run

1. Clone or download this repository.
2. Ensure that Python and Jupyter Notebook are installed.
3. Install the required libraries by running the following command:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

4. Open `assignment1_eda.ipynb` in Jupyter Notebook or Visual Studio Code.
5. Run the notebook cells from top to bottom.

Ensure that `Zomato Dataset.csv` remains inside the `data/` directory so that the notebook can load the dataset using its relative file path.

## 6. Analysis Covered

This project includes:

- Scenario and dataset overview
- Dataset source and acquisition method
- Missing value identification and handling decisions
- Outlier detection using the IQR method and boxplots
- Duplicate, invalid value, and data type checks
- Diagnostic charts for data quality issues
- Potential PII and bias risks
- Conclusion on dataset suitability and limitations

## 7. Team Members

| No. | Name | Matric Number |
|---|---|---|
| 1 | MUHAMAD ALIF ZULHILMI BIN MOHD ASRI] | A208626 |
| 2 | MUHAMMAD AIMAN SYAFIQ BIN MOHD HANAFI| A213793 |
| 3 | AHMAD DANISH FARHAN BIN AHMAD ZAWANI | A208439 |
| 4 | MOKEISH RAJAN BASKARAN| A212069 |

## 8. Conclusion

This project demonstrates how data profiling can identify and address data quality issues before further analysis. The findings also highlight the importance of considering missing data, unusual values, privacy risks, and potential bias when assessing dataset suitability.
