# Hypertension Analysis

This project analyzes a dataset of individuals with features related to hypertension, such as age, salt intake, stress score, BMI, medication use, and more. The aim is to explore how these factors relate to the presence of hypertension.

## Project Overview

The notebook performs the following steps:
- **Loads** a CSV dataset containing health and lifestyle attributes of 1985 participants.
- **Explores** the structure of the data (columns, types, sample entries).
- **Handles missing values** (e.g., fills empty medication values with "No Medication").
- **Provides descriptive statistics** for numerical features.
- **Counts the number of hypertensive and non-hypertensive individuals**.

## Dataset Columns

| Column             | Description                                               |
|--------------------|----------------------------------------------------------|
| `Age`              | Age of the participant (years)                           |
| `Salt_Intake`      | Estimated daily salt intake (grams)                      |
| `Stress_Score`     | Stress level on a scale from 0 to 10                     |
| `BP_History`       | Blood pressure history (Normal, Prehypertension, etc.)   |
| `Sleep_Duration`   | Average daily sleep duration (hours)                     |
| `BMI`              | Body Mass Index                                          |
| `Medication`       | Medication used (if any, else "No Medication")           |
| `Family_History`   | Family history of hypertension (Yes/No)                  |
| `Exercise_Level`   | Exercise frequency (Low, Moderate, etc.)                 |
| `Smoking_Status`   | Smoking status (Non-Smoker, Smoker)                      |
| `Has_Hypertension` | Whether the participant has hypertension (Yes/No)        |

## Main Steps in the Notebook

1. **Import Libraries**  
   Uses Python's `pandas` library for data handling.

2. **Load Data**  
   Reads the CSV file into a DataFrame.

3. **Data Inspection**  
   - Prints info about columns and types
   - Shows sample data entries

4. **Missing Values Handling**  
   - Counts missing values per column
   - Fills missing values in the `Medication` column with `"No Medication"`

5. **Descriptive Statistics**  
   - Provides summary statistics for numerical features (mean, std, min, max, etc.)

6. **Target Variable Distribution**  
   - Shows the distribution of the `Has_Hypertension` column

## How to Use

1. **Clone the repository**  
   ```bash
   git clone https://github.com/ardabulut46/hypertension-analysis.git
   cd hypertension-analysis
   ```

2. **Open the Notebook**  
   Open `hypertension.ipynb` in Jupyter Notebook or Google Colab.

3. **Upload the Dataset**  
   Make sure the `hypertension_dataset.csv` file is placed in `/content/sample_data/` if running on Colab, or adjust the path as needed.

4. **Run the Notebook Cells**  
   Execute each cell step by step to see the analysis and outputs.

## Requirements

- Python 3.x
- pandas

If running locally, install dependencies with:
```bash
pip install pandas
```

## Example Insights

- The dataset contains 1985 entries.
- About half have hypertension.
- Features like salt intake, BMI, stress, and sleep vary widely and are analyzed for their relationship with hypertension.

## License

This project is for educational and analytical purposes.

## Author

[ardabulut46](https://github.com/ardabulut46)
