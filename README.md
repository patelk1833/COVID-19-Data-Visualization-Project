# COVID-19 Data Visualization Project
### **By**: Krish Patel
### **Date**: July 28th, 2023
## Project Overview
This project involves analyzing COVID-19 data to uncover meaningful insights and trends through data visualization techniques. It combines data collection, cleaning, analysis, and the development of an interactive **Shiny Dashboard** to present findings. The project utilizes data from the [Johns Hopkins CSSE COVID-19 GitHub Repository](https://github.com/CSSEGISandData/COVID-19).

[**Dashboard**](https://patelk22.shinyapps.io/myapp/) 

## Project Goals
- Automate the collection of reliable COVID-19 data from the Johns Hopkins repository.  
- Clean and preprocess the raw data for analytical readiness.  
- Develop reusable visualization functions to create dynamic and interactive plots.  
- Build an intuitive and user-friendly _**Shiny Dashboard**_ for exploring the data.

## Methodology
1. **_Data Collection_**: Involved sourcing data from the **_Johns Hopkins CSSE COVID-19 GitHub Repository_**, a reliable and up-to-date source for global COVID-19 statistics. Automated scripts written in **_R_** were used to fetch daily reports, ensuring consistent and timely data acquisition.  

2. **_Data Cleaning & Preparation_**: Focused on addressing missing values and formatting dates to maintain data integrity. Relevant columns for confirmed cases, deaths, and recovered metrics were filtered to streamline the dataset. To gain deeper insights, data was aggregated at the state level, allowing for more targeted analysis.  

3. **_Data Visualization_**: Utilized custom-built functions to dynamically visualize key metrics. These included total cases, daily new cases, total deaths, daily deaths, and mortality rates. This approach enabled a clear understanding of trends and patterns in the data.  

4. **_Interactive Dashboard_**: Development was carried out using **_Shiny_**, a web application framework for **_R_**. The dashboard allowed users to select parameters such as state and date range, enabling them to interactively explore data trends and derive actionable insights.

## Key Findings
- **Dynamic Trends**: National trends in confirmed and active COVID-19 cases revealed distinct waves of outbreaks, highlighting the **cyclical nature of the pandemic** and its progression over time.  
- **State-Level Insights**: Certain states demonstrated significantly higher infection and mortality rates, emphasizing the need for **targeted interventions** and localized health policies to manage the impact effectively.  
- **_Mortality Patterns_**: Logarithmic scaling of the data uncovered **_notable spikes in mortality_** during specific time periods, providing valuable insights into the **_severity and progression of the pandemic_** across different regions.  

## Conclusion
The COVID-19 Data Visualization Project effectively analyzed pandemic trends using data from the _**Johns Hopkins repository**_. It highlighted key insights such as outbreak waves, state-level disparities, and mortality patterns, while the interactive _**Shiny Dashboard**_ enabled users to explore trends dynamically. This project showcases a comprehensive approach to data analysis and visualization, providing valuable tools for informed decision-making.

## Resources Used
- **_Programming Language_**: **R**  
- **_Libraries_**: **Tidyverse**, **Shiny**  
- **_Tools_**: **Shiny App**  
- **_Data source_**: [**Johns Hopkins CSSE COVID-19 GitHub Repository**](https://github.com/CSSEGISandData/COVID-19)  

## Key Skills Demonstrated
- **Data collection and preprocessing**  
- **Dynamic visualization creation**  
- **Shiny Dashboard development**  
- **Exploratory data analysis**

## Repository
- **Dashboard Link**: Contains the link to the hosted dashboard.  [**Dashboard**](https://patelk22.shinyapps.io/myapp/)  
- **covid_data (Excel)**: Raw COVID-19 dataset.  
- **covid_data_new (Excel)**: Cleaned/updated COVID-19 dataset.  
- **Covid19_Data_Visualization (Jupyter)**: R code for analysis and visualization.  
- **Running_App (Jupyter)**: Code to execute the **Shiny Dashboard** locally.  




