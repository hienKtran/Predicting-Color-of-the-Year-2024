# Data Wrangling Project: Pantone’s Color of the Year vs. Global Happiness Scale
### Tools Used
![R Studio badge](https://img.shields.io/static/v1?message=R%20Studio&logo=RStudio&labelColor=75AADB&color=75AADB&logoColor=white&label=%20&style=for-the-badge)
---
### 1. Introduction
This project explores predictions for Pantone's 2024 Color of the Year and its correlation with global happiness factors.

### 2. Data
#### 2.1 Pantone Color of the Year
- Utilizes Approval Studio's article on Pantone Colors of the Year up to 2023.
- Extracts Pantone color data including year, color name, ID, hexadecimal code, and summary using R's "xml2" package.
- Adds a new column for RGB values and calculates light value and hue.
#### 2.2 World Happiness Report up to 2023
- Uses Kaggle's 'World Happiness Report up to 2023' for 158 countries from 2015 to 2023.
- Organizes data by year and merges using 'dplyr' and 'tidyr' in R.
#### 2.3 Data Collection and Preparation
Scrapes Pantone data and cleans it for analysis.
Combines World Happiness Reports and filters data for relevant years.
Merges datasets to create a comprehensive dataset for analysis.
### 3. Analysis
#### 3.1 Hexadecimal Code Analysis
- Derives RGB values from hexadecimal codes and calculates hue and lightness using R.
- Analyzes trends in color characteristics and provides insights into color preferences.
#### 3.2 Correlation Analysis
- Investigates correlations between Color of the Year hue and GDP scores using statistical analysis and visualization.
- Explores correlations between World Happiness Report factors and Color of the Year selections.
- Identifies trends and relationships between color choices and external factors.
#### 4. Conclusion
- Summarizes findings from color analysis and correlation investigations.
- Discusses insights into Pantone's Color of the Year choices and their relationship with external factors.
- Highlights limitations and potential for further research in color analysis and preference studies.
### 5. Limitations
- Acknowledges limitations in correlating color choices with external factors like GDP.
- Discusses the potential value of the analysis despite these limitations.

For more details, refer to the full analysis and data dictionary in the project documentation.
