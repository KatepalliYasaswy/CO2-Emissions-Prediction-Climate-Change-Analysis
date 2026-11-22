# 🌍 CO₂ Emissions Prediction Using Country-Specific Data

### Climate Change Analysis | Data Science | Environmental Analytics

<p align="center">
  <strong>Transforming Environmental Data into Meaningful Insights for a Sustainable Future.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Domain-Climate%20Analytics-2E8B57" />
</p>

---

## 🌱 About the Project

Climate change is one of the most significant global challenges, and carbon dioxide (CO₂) emissions play an important role in environmental changes.

This project focuses on analyzing country-specific climate, economic, demographic, and energy-related indicators to understand their relationship with CO₂ emissions.

Using Python and data science techniques, the project explores raw environmental datasets, performs data cleaning and preprocessing, handles missing values, and transforms complex datasets into a structured format for further analysis.

The objective is to establish a reliable data foundation for understanding environmental patterns and supporting future CO₂ emissions prediction.

## 🎯 Project Objectives

- Analyze country-specific environmental and socioeconomic indicators.
- Explore historical CO₂ emission patterns.
- Understand the relationship between energy consumption and emissions.
- Examine the influence of economic and demographic factors.
- Handle missing values and inconsistencies in raw datasets.
- Prepare structured data for exploratory analysis and predictive modeling.

## 📊 Dataset Overview

The project uses a country-specific climate change dataset containing environmental and socioeconomic indicators.

**Original Dataset:**
- Records: 13,512
- Columns: 28
- Countries and geographical entities: 233
- Environmental and socioeconomic indicators: 58
- Time period: 1990–2011

### Key Data Categories

| Category | Indicators |
|:--|:--|
| 🌍 Greenhouse Gas Emissions | CO₂, methane and nitrous oxide emissions |
| ⚡ Energy | Energy consumption per capita and per GDP |
| 💰 Economy | GDP, GNI and foreign direct investment |
| 👥 Demographics | Population and urban population growth |
| 🌾 Agriculture | Cereal yield |
| 🌳 Environment | Protected land areas and natural disaster indicators |
| 🏥 Health | Under-five mortality rate |

## ⚙️ Project Workflow

### 1. Data Understanding

- Imported the original Excel dataset using Pandas.
- Examined dataset dimensions, column names and data types.
- Inspected unique values and descriptive statistics.
- Identified unnecessary columns and missing-value indicators.

### 2. Data Cleaning

- Removed non-numeric and irrelevant records.
- Eliminated unnecessary columns.
- Replaced missing-value indicators such as `..` with NaN.
- Converted appropriate columns into numerical data types.
- Renamed lengthy feature descriptions into meaningful variable names.

### 3. Data Transformation

- Converted the dataset from a wide format into a structured format.
- Used Pandas `melt()` to reshape year-wise observations.
- Combined multiple environmental indicators using country and year.
- Prepared a unified country-level dataset.

### 4. Missing Value Treatment

- Analyzed missing values across different years and countries.
- Selected the period from 1991 to 2008.
- Filtered countries based on missing-value counts.
- Removed features containing more than 20 missing values.
- Eliminated remaining incomplete observations.

### 5. Final Dataset Preparation

- Validated the cleaned dataset.
- Verified that no missing values remained.
- Exported the processed dataset for further analysis.

## 📈 Data Preparation Results

| Dataset Stage | Records | Columns |
|:--|--:|--:|
| Original Dataset | 13,512 | 28 |
| After removing text-scale records | 10,017 | 24 |
| After reshaping and merging | 5,126 | 23 |
| After year filtering | 4,194 | 23 |
| After country filtering | 1,728 | 23 |
| Final cleaned dataset | 1,700 | 18 |

<details>
<summary><strong>View final cleaned dataset features</strong></summary>

| Feature | Description |
|:--|:--|
| country | Country code |
| year | Observation year |
| cereal_yield | Cereal yield |
| fdi_perc_gdp | Foreign direct investment as % of GDP |
| en_per_gdp | Energy use per unit of GDP |
| en_per_cap | Energy use per capita |
| co2_ttl | Total CO₂ emissions |
| co2_per_cap | CO₂ emissions per capita |
| co2_per_gdp | CO₂ emissions per unit of GDP |
| pop_urb_aggl_perc | Population in urban agglomerations |
| prot_area_perc | Protected land area percentage |
| gdp | Gross Domestic Product |
| gni_per_cap | Gross National Income per capita |
| under_5_mort_rate | Under-five mortality rate |
| pop_growth_perc | Population growth percentage |
| pop | Total population |
| urb_pop_growth_perc | Urban population growth |
| urb_pop | Urban population |

</details>

## 🛠️ Technology Stack

| Category | Technologies |
|:--|:--|
| Programming Language | Python |
| Data Manipulation | Pandas |
| Numerical Computing | NumPy |
| Data Storage | Excel, CSV |
| Development Environment | Jupyter Notebook |

## 📁 Project Structure

```text
CO2-Emissions-Prediction/
│
├── 1_data_preparation.ipynb
│
├── 2_data_exploration.ipynb
│
├── climate_change_download_0.xlsx
│
├── data_cleaned.xlsx
│
├── certificates/
│   └── edunet-certificate.pdf
│
└── README.md
```

## 🚀 Getting Started

Follow these steps to run the project locally.

**1. Clone the repository**

```bash
git clone https://github.com/your-username/CO2-Emissions-Prediction.git
```

**2. Navigate to the project directory**

```bash
cd CO2-Emissions-Prediction
```

**3. Install the required libraries**

```bash
pip install pandas numpy openpyxl jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

**5. Execute the notebooks**

Run the notebooks to explore the data preparation and exploration workflow.

## 🔮 Future Enhancements

The prepared dataset provides a foundation for extending the project with:

- Exploratory data analysis and interactive visualizations.
- Country-wise and year-wise CO₂ emissions comparisons.
- Correlation analysis between economic and environmental indicators.
- Machine learning models for CO₂ emissions prediction.
- Model evaluation using MAE, RMSE and R².
- Interactive environmental analytics dashboard.

## 📜 Certification

**Edunet Foundation**

This project was developed as part of the Edunet Foundation learning experience.

**Project Domain:** Climate Change Analysis and Data Science

**Project Title:** Prediction of CO₂ Emissions from Country-Specific Data

📄 **Certificate:** [View Certificate](certificates/edunet-certificate.pdf)

## 💡 Skills Demonstrated

`Python` · `Data Cleaning` · `Data Preprocessing` · `Pandas` · `NumPy` · `Exploratory Data Analysis` · `Feature Engineering` · `Missing Value Treatment` · `Environmental Data Analytics`

---

<p align="center">
  <strong>🌍 Using Data Science to Understand Environmental Challenges.</strong>
</p>

<p align="center">
  ⭐ If you find this project interesting, consider giving this repository a star!
</p>
