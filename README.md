# Price Manipulation in the Canadian Grocery Sector

## 📊 Overview

This project analyses price manipulation in the Canadian grocery sector by examining price trends before and after sales. The analysis investigates whether prices are artificially inflated just before a sale, only to be reduced back to normal afterward. The study uses a combination of data wrangling, statistical analysis, and visualisation to uncover patterns in grocery prices.

The dataset used in this project is from https://jacobfilipp.com/hammer/ it is publicly available and contains data on grocery prices, sale periods, and product information. The analysis was conducted using Python and various data science libraries such as Pandas, NumPy, and SciPy. Certain data files are too large to be made available on GitHub, please visit the following link to access them: https://drive.google.com/drive/folders/1-i4Q9cEgtIJILTofSd93w5-B2fQLRpaz?usp=drive_link . Download the files and place them into a folder called 'Data' within the main project folder.


## 📂 File Structure

The repo is structured as:

-   `00-simulated_data.parquet` contains the simulated data
-   `raw_data.csv` contains the raw data as obtained from Jacobfilipp.com/hammer/
-   `cleaned_price_data.parquet` contains the cleaned analysis dataset that was constructed
-   `models` contains a fitted model
-   `other` contains details about LLM usage and sketches
-   `paper` contains the paper
-   `scripts` contains the python scripts used to work with the dataset and perform various tasks

## 💬 LLM Usage
Aspects of the project (albeit negligible) involved the use of ChatGPT 4.0 for ideas generation. This is documented in other/llm_usage/usage.txt

## Help
-   Certain scripts may not run as expected in Visual Studio Code if the necessary extensions and packages are not installed. To overcome potential errors, use CMD/ctrl + Shift + X to browse the extensions marketplace, search for and install Python, Quarto, R, Jupyter, and Data Wrangler. Certain Python packages may need to be installed using the terminal. To do so, paste: "python3 -m pip install pandas numpy matplotlib seaborn pyyaml nbformat nbclient scipy stats pyarrow tabulate" into the terminal.
-   In case the references at the bottom of the pdf fail to render/import from references.bib, please view the BibTex file directly.
