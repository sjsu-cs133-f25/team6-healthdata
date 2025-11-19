# team6-healthdata

Group members:  Erica Xue, Tehkhum Sultanali, Shaswat Sharma, Sam Matharu


# Dataset Description
This dataset is derived from the CDC’s Behavioral Risk Factor Surveillance System (BRFSS), which is the world’s largest continuously conducted health survey system. Each year, BRFSS collects responses from over 400,000 adults across all 50 states, the District of Columbia, and U.S. territories, tracking a wide range of health-related behaviors and conditions.

The Kaggle dataset we are using is a cleaned, 2022 version of this data, reduced to 40 of the most relevant variables connected to heart disease, including:

- Demographics: State, sex, age group, race/ethnicity
- General health & habits: Self-rated health, sleep hours, physical activity, smoking, e-cigarette use, alcohol consumption
- Medical history: Past diagnoses (e.g., asthma, COPD, diabetes, arthritis, kidney disease, skin cancer)
- Functional/behavioral challenges: Difficulty walking, concentrating, daily errands
- Preventive care & testing: Flu vaccine, tetanus, chest scans, COVID test results
- Heart disease indicators: History of heart attack, angina, or stroke


# Dataset Download
1. Go to https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease/data
2. Log in to your Kaggle account (or sign up if you don't have one)
3. Under the **Data Card** tab, select **heart_2022_no_nans.csv**, and click **Download**. This will download as a .zip file.
4. Unzip the dataset file

# Dependencies
The project runs in Google Colab.
To run it locally, install the following libraries:
- pandas
- matplotlib
- seaborn
- numpy
- panel
- plotly
- scipy

This can be done by: ```pip install pandas matplotlib seaborn numpy panel plotly scipy```

# How to Run
1. Download the Colab notebook (.ipynb file) under the **Notebook** directory in this repository
2. Open the Colab notebook in Google Colab
3. Upload the dataset (heart_2022_no_nans.csv) to the notebook environment
4. Run all the cells to replicate the results

