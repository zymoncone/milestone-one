# Milestone I ✌️
Welcome to the University of Michigan MADS Milestone I repo for group 19 👋 Here you can find all our data exploration and visualization code 👩‍💻

## Project Description
This project aims to analyze trends between hospital resources and Covid-19 deaths. Covid continues to be a massive topic of discussion, and the team is interested in viewing the trends over time AND trends between urban and rural areas. The scope will be the United States, which public government data is available for.

## Dataset Descriptions

### Primary Dataset

✍️**Short Description:** The primary dataset is a comprehensive collection of U.S. hospital capacity statistics related to COVID-19, which includes metrics such as total beds available, inpatient beds used, ICU capacity, and COVID-19 admissions.

💾**Estimated Size:** Approximately `448MB`, with 335,066 records across 128 features.

📍**Location:** [healthdata.gov](https://healthdata.gov/Hospital/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/anag-cw7u/about_data "primary dataset")

💽**Format:** The dataset is available in CSV format.

🔑**Access Method:** The data was downloaded directly from the HealthData.gov website.

The key features of this dataset include hospital identifiers, location information, hospital subtype, metrics on bed availability and usage, COVID-19 impact on hospital resources, and influenza statistics. The dataset is expected to be used for analyzing the impact of COVID-19 on hospital resources and capacity over time.

### Secondary Dataset

✍️**Short Description:** The secondary dataset provides weekly updates on COVID-19 cases and deaths by state and county in the United States.

💾**Estimated Size:** Roughly `27MB`, with 566,056 records and 9 features.

📍**Location:** [data.cdc.gov](https://data.cdc.gov/dataset/Weekly-United-States-COVID-19-Cases-and-Deaths-by-/yviw-z6j5/data_preview "secondary dataset")

💽**Format:** The dataset is available in CSV format.

🔑**Access Method:** The data was downloaded directly from the CDC's website.

The secondary dataset's key features include FIPS codes, county and state identifiers, dates, and cumulative as well as new cases and deaths due to COVID-19. This dataset would be used to complement the primary dataset by providing epidemiological data on COVID-19, allowing for a combined analysis of health outcomes and hospital capacity.

## Jupyter Notebook Set-Up
To run a .ipynb (Jupyter Notebook) file locally in Visual Studio Code (VS Code), you'll need to have Jupyter installed in your Python environment. Follow these steps:

**1. Install Jupyter:** If you haven't installed Jupyter, you can install it via pip:

```bash
pip install jupyter
```

**2. Open VS Code:** Open your Visual Studio Code editor.

**3. Install Python Extension:** Make sure you have the Python extension installed in VS Code. You can find and install it from the Extensions view (Ctrl+Shift+X) by searching for "Python".

**4. Open the .ipynb File:** Open the .ipynb file you want to run in VS Code.

**5. Select Python Interpreter:** Click on the Python interpreter version at the bottom-left corner of the VS Code window and select the Python interpreter that has Jupyter installed.

**6. Run Cells:** You can now run individual cells or the entire notebook. To run a cell, you can use the shortcut Ctrl+Enter or use the "Run Cell" option in the cell's context menu (right-click on the cell).

**7. Using the Jupyter Extension:** Alternatively, you can install the "Jupyter" extension in VS Code, which provides richer support for Jupyter Notebooks. You can find and install this extension from the Extensions view in VS Code.

**8. Execute Notebook:** With the Jupyter extension installed, you'll see additional options for running and managing Jupyter Notebooks directly in VS Code's notebook interface.