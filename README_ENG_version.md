
> [!Note] 
> This Jupyter Notebook performs analysis in Japan Standard Time (JST). Please change the time zone as needed. (We're sorry, but we can't support changing the time zone.)
> We are considering creating an English version of the Jupyter Notebook (.ipynb) if there is sufficient demand.

## Introduction
- In this notebook, we will analyze sleep data based on Google Fit data.
- Please [download the data from Google Fit](https://takeout.google.com/).
- If you prefer to analyze in Japanese, please use `/Sleep_Analyze_Notebook_JP_version.ipynb`.
- This notebook allows for seamless analysis even for users like the author who track sleep using **multiple devices**.
- Please run the cells **one at a time, not all at once**.

## Data Analysis Flow
1. Import modules
2. Load data
3. (If manual sleep records exist) Select the dataset
4. (If necessary) Export the data as a CSV file
5. Visualize quarterly sleep records using an actogram

    <img src="Sample_Actogram.png" width="320px" alt="Access Google data export and deselect All">
    
6. Quarterly statistics
7. Visualize sleep records for specific dates

    <img src="Sample_Sleep_cycle.png" width="320px" alt="Access Google data export and deselect All">