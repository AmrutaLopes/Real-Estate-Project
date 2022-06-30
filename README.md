# Real Estate - Data Science Capstone Project : Project Overview
### Project Description :-

- A banking institution requires actionable insights into mortgage-backed securities, geographic business investment, and real estate analysis. 
- The mortgage bank would like to identify potential monthly mortgage expenses for each region based on monthly family income and rental of the real estate.
- A statistical model needs to be created to predict the potential demand in dollars amount of loan for each of the region in the USA. Also, there is a need to create a dashboard which would refresh periodically post data retrieval from the agencies.
- The dashboard must demonstrate relationships and trends for the key metrics as follows: Average rent distribution by type, Pie charts for debt analysis,Geo-Map for top locations based on second mortgage and percentage of ownership,Heatmap for correlation matrix,Pie chart for population density.

### Tools and technologies used:
* Python Version: 3.8.5
* Packages and Libraries used:- 
  * a. Visualization libraries : Matplotlib,Seaborn,Plotly
  * b. Data Analysis,arrays,factor analysis: Numpy,Pandas,Factor Analyzer
  * c. Scaling,Model building,accuracy metric check: Scikit learn

### Steps
1. **Data Import and Preparation:** 
    * a. Imported the required dataset 
    * b. Gauge the missing value rate and imputed 'na' values with median
   
2. **Exploratory Data Analysis (EDA):**
   * a. Explored the top 2500 locations based on second mortgage and pct_own variables with specific condition and
        visualized it using geo map
   * b. Performed Debt analysis for all states combined and visualized by pie-chart.
   * c. City wise mortgage,home_equity loan and debt analysis by boxplot plots.
   * d. Visualization of Income distribution overall.
   * e. Dive into population spread across all the states and percentage of income based on states
   * f. Heatmap for correlation analysis to check the rleationship between independent and target variables
   
3. **Data Pre-processing:**
   * Used Factor analyzer python module to perform factor analysis,to find where the measured variables depend on a number      of smaller unobserved common factors or latent variables.
   
4. **Data Modelling:**
   * Built a linear Regression model to predict the total monthly expenditure for home mortgages loan by using independent      features of importance.
   * Regression model built on national and states level.
   
5. **Model Performace(LinearRegression):**
   * **R-squared value**   : 0.7999
   * **RMSE value**        : 281.39
   * **Adjusted R-squared** 0.7989

### Data Reporting
#### Tableau Public Dashboard Link
https://public.tableau.com/app/profile/amruta/viz/RealEstate_16556405910430/RealEstateDashboard

