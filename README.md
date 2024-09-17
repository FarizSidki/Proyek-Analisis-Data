# Proyek Analisis Data - Dicoding

[Dashboard Streamlit App](https://farizdicoding.streamlit.app/)

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)

## Overview
This project focuses on data analysis and visualization of public e-commerce data. It includes code for data wrangling, exploratory data analysis (EDA), and an interactive dashboard built with Streamlit. The goal is to analyze the E-Commerce Public Dataset.

## Project Structure
- `dashboard/`: This directory contains dashboard.py which is used to create dashboards of data analysis results.
- `data/`: Directory containing the raw CSV data files.
- `notebook.ipynb`: This file is used to perform data analysis.
- `README.md`: This documentation file.
- `requirement.txt`: This file containing various libraries used in the data analysis process. 
- `url.txt`: This file containing Uniform Resource Locators (URLs) for the streamlit app dashboard. 

## Installation
1. Clone this repository to your local machine:
```
git clone https://github.com/FarizSidki/Proyek-Analisis-Data.git
```
2. Go to the project directory
```
cd Proyek-Analisis-Data
```
3. Install the required Python packages by running:
```
pip install -r requirements.txt
```

## Usage
1. **Data Wrangling**: Data wrangling scripts are available in the `notebook.ipynb` file to prepare and clean the data.

2. **Exploratory Data Analysis (EDA)**: Explore and analyze the data using the provided Python scripts. EDA insights can guide your understanding of e-commerce public data patterns.

3. **Visualization**: Run the Streamlit dashboard for interactive data exploration:

```
cd Proyek-Analisis-Data/dashboard
streamlit run dashboard.py
```
Access the dashboard in your web browser at `http://localhost:8501`.

## Data Sources
The project uses E-Commerce Public Dataset from [Proyek Akhir Belajar Analisis Data dengan Python](https://drive.google.com/file/d/1MsAjPM7oKtVfJL_wRp1qmCajtSG1mdcK/view) offered by [Dicoding](https://www.dicoding.com/).
