# Price Manipulation in the Canadian Grocery Sector

## 📊 Overview

This project analyses price manipulation in the Canadian grocery sector by examining price trends before and after sales. The analysis investigates whether prices are artificially inflated just before a sale, only to be reduced back to normal afterward. The study uses a combination of data wrangling, statistical analysis, and visualisation to uncover patterns in grocery prices.

The dataset used in this project is publicly available and contains data on grocery prices, sale periods, and product information. The analysis was conducted using Python and various data science libraries such as Pandas, NumPy, and SciPy.


## 📂 File Structure

The repo is structured as:

-   `00-simulated_data.parquet` contains the simulated data
-   `raw_data.csv` contains the raw data as obtained from Jacobfilipp.com/hammer/
-   `cleaned_price_data.parquet` contains the cleaned analysis dataset that was constructed
-   `models` contains a fitted model
-   `other` contains details about LLM usage and sketches
-   `paper` contains the paper
-   `scripts` contains the python scripts used to work with the dataset and perform various tasks

* A Google Drive link to the data folder has been placed in `data` for the time being since all files are over 25MB and cannot be uploaded directly to GitHub

## 💬 LLM Usage
Aspects of the project (albeit negligible) involved the use of ChatGPT 4.0 for ideas generation. This is documented in other/llm_usage/usage.txt

## Help
Certain scripts may not run as expected in Visual Studio Code if the necessary extensions and packages are not installed. To overcome potential errors, use CMD/ctrl + Shift + X to browse the extensions marketplace, search for and install Python, Quarto, R, Jupyter, and Data Wrangler. Certain Python packages may need to be installed using the terminal. To do so, paste: "python3 -m pip install pandas numpy matplotlib seaborn pyyaml nbformat nbclient scipy" into the terminal.
