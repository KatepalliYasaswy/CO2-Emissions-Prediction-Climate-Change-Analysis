# 🌍 CO₂ Emissions Prediction Using Country-Specific Data

### Climate Change Analysis | Data Science | Environmental Analytics

<p align="center">
  <strong>Exploring the relationship between economic, demographic, and environmental indicators to understand CO₂ emissions across countries.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Science-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Domain-Climate%20Analytics-2E8B57" />
</p>

---

## 🌱 Project Overview

Climate change is one of the major global challenges, with carbon dioxide (CO₂) emissions playing a significant role in environmental changes.

This project focuses on exploring country-specific climate, economic, demographic, energy, and environmental indicators to understand their relationship with CO₂ emissions.

Using data science techniques, the project involves examining the original dataset, cleaning and transforming raw data, handling missing values, and preparing a structured dataset for further analysis and predictive modeling.

## 🎯 Project Objectives

- Analyze country-specific climate and socioeconomic indicators.
- Understand patterns in CO₂ emissions across different countries.
- Investigate relationships between economic growth, energy consumption, and emissions.
- Clean and transform raw climate datasets into structured data.
- Prepare reliable data for further exploratory analysis and machine learning.

## 📊 Dataset Overview

The project uses a country-specific climate change dataset containing **13,512 records and 28 columns** in its original Data sheet.

The dataset includes indicators related to:

| Category | Key Indicators |
|:--|:--|
| 🌍 Greenhouse Gas Emissions | CO₂, methane and nitrous oxide emissions |
| ⚡ Energy | Energy consumption per capita and per GDP |
| 💰 Economy | GDP, GNI and foreign direct investment |
| 👥 Demographics | Population, urban population and population growth |
| 🌾 Agriculture | Cereal yield |
| 🌳 Environment | Protected land areas and natural disaster indicators |
| 🏥 Health | Under-five mortality rate |

**Time period selected for cleaned data:** 1991–2008.

## ⚙️ Project Workflow

### 1. Data Preparation

- Imported the original Excel dataset using Pandas.
- Examined dataset dimensions, data types and descriptive statistics.
- Identified missing values and unnecessary columns.
- Removed irrelevant records and columns.
- Converted missing-value indicators into NaN.
- Transformed numerical columns into appropriate data types.

### 2. Data Transformation

- Renamed lengthy feature descriptions into meaningful variable names.
- Restructured the dataset using melting and pivot-style transformations.
- Organized the observations by country and year.
- Consolidated individual climate indicators into a unified dataset.

### 3. Missing Value Handling

- Examined missing values across years and countries.
- Selected the 1991–2008 period to reduce missing data.
- Filtered countries based on missing-value counts.
- Removed features with more than 20 missing values.
- Eliminated remaining incomplete observations.

### 4. Data Exploration

Performed initial dataset inspection and prepared the cleaned data for subsequent exploratory analysis and predictive modeling.

## 🛠️ Technology Stack

| Category | Technologies |
|:--|:--|
| Programming Language | Python |
| Data Manipulation | Pandas |
| Numerical Computing | NumPy |
| Data Storage | Excel, CSV |
| Development Environment | Jupyter Notebook |
| Data Analysis | Exploratory Data Analysis |

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
└── README.md
```

## 📈 Cleaned Dataset

The final cleaned dataset contains:

- **1,700 data records**
- **18 columns**
- Country and year identifiers
- 16 country-specific numerical indicators
- Data covering 1991–2008

The cleaned dataset is structured for further climate analysis and predictive modeling.

## 🚀 Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/your-username/CO2-Emissions-Prediction.git
```

**2. Navigate to the project directory**

```bash
cd CO2-Emissions-Prediction
```

**3. Install dependencies**

```bash
pip install pandas numpy openpyxl jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

**5. Execute the notebooks**

Run the notebooks in the following order:

1. `1_data_preparation.ipynb`
2. `2_data_exploration.ipynb`

## 🔍 Expected Project Direction

The prepared dataset provides a foundation for further investigation into:

- Relationships between CO₂ emissions and economic indicators.
- Energy consumption and environmental impact.
- Country-level differences in emissions.
- Predictive modeling of climate-related indicators.

## 💡 Skills Demonstrated

`Python` · `Data Cleaning` · `Data Preprocessing` · `Pandas` · `NumPy` · `Exploratory Data Analysis` · `Feature Engineering` · `Missing Value Treatment` · `Environmental Data Analytics`

---

<p align="center">
  <strong>🌍 Using Data Science to Understand Environmental Challenges.</strong>
</p>

<p align="center">
  ⭐ If you find this project interesting, consider giving it a star!
</p>
