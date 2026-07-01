
```markdown
# Soil Moisture Exploratory Data Analysis (EDA)

## Project Overview
This project looks at soil moisture data along with latitude and longitude.  
The goal is to understand how soil moisture varies and whether it depends on geographic position.


## What Was Done
1. **Dataset Overview**  
   - Variables: soil moisture, latitude, longitude  
   - Coordinates provide location context but are not strong predictors of soil moisture.  

2. **Exploratory Data Analysis (EDA)**  
   - Scatter plots : show very weak trends with latitude and longitude.  
   - Correlation heatmap : confirms weak correlations (~+0.07, ~−0.10).  
   - Pair plot : combines scatter plots and KDE distributions; shows mid‑range soil moisture values and uneven sampling across coordinates.  
   - Histogram + KDE : soil moisture distribution is right‑skewed (mostly moderate values, few very high outliers).  

3. **Key Findings**  
   - Soil moisture is mostly moderate.  
   - A few extreme wet values create a right‑skewed distribution.  
   - Latitude and longitude have only weak influence.  
   - Local environmental factors (rainfall, soil type, vegetation) matter more.  

4. **Challenges Encountered**  
   - Weak correlations made it hard to find strong geographic patterns.  
   - Skewed distribution required careful interpretation.  
   - Uneven sampling across latitude/longitude bands.

## Installation

i). **Clone the Repository**
   ```bash
   git clone https://github.com/VishnuIITP/Soil_Moist_analysis.git
   cd Soil_Moist_analysis

ii). **Set Up Python Environment**
   - Install Python 3.9 or higher.
   - (Optional but recommended) Create a virtual environment:
     ```bash
     python -m venv venv
     source venv/bin/activate   # Linux/Mac
     venv\Scripts\activate      # Windows
     ```

iii). **Install Dependencies**
   - Install required libraries:
     ```bash
     pip install -r requirements.txt
     ```
   - Typical dependencies include:
     - pandas  
     - numpy  
     - matplotlib  
     - seaborn  
     - scikit-learn

iv0. **Verify Installation**
   - Run a quick check:
     ```bash
     python eda.py
     ```
   - If everything is installed correctly, plots and results will be generated in the `results/` folder.
  

## Final Observations
Soil moisture variation is **not strongly explained by latitude or longitude**.  
Most values are moderate, with rare high outliers.  
Local conditions are more important than coordinates in driving soil moisture.
```

