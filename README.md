# Crop Burning and Air Quality in South Asia

## Overview

This project explores the relationship between crop burning and air quality in South Asian nations. The analysis addresses three main questions:

1. Examine the relationships between crop burning and the air quality index, generalized for all of South Asia.
2. Identify the South Asian country with the highest incidence of crop burning and assess its contribution to air quality.
3. Utilize forecasting techniques to predict the trajectory of the identified country in the coming years.

## Project Structure

- **Data Collection and Wrangling:** The project involves downloading data from various sources, including the World Bank, Kaggle, and ClimateWatch. The datasets are cleaned and summarized on a yearly basis.

- **Data Exploration:** Visualizations are generated to observe general trends and characteristics within the data. Exploratory data analysis is conducted, including trend analysis of crop emissions in South Asian countries and the trend in the Air Quality Index values.

- **Data Transformation:** Mathematical transformations are applied to the data to ensure adherence to the assumptions of the intended model. The analysis includes correlation testing between variables and the application of a rolling average to enhance correlation.

- **Fitting a Linear Model:** A linear regression model is proposed, and hypotheses are formulated. The model output is analyzed to determine the strength of the correlation between the air quality index and crop residues.

- **Part B:** The analysis is replicated for a specific country (Bangladesh) with a focus on emissions per unit of cultivable area. Linear regression is applied to assess the relationship between crop residues and air quality in Bangladesh.

- **Further Exploration:** Time series analysis is conducted using monthly data to uncover nuanced trends in air quality in Bangladesh. Forecasting techniques are applied to predict air quality index values in the coming years.

- **Next Steps:** Future steps for the project include evaluating the accuracy of forecasting models, gathering monthly data specifically for crop emissions, and leveraging World Bank data for clustering countries based on CO2 emissions.

## Code

The end-to-end code for this project is available on [GitHub](https://github.com/Sujan-Bhattarai12/southasia_aqi.git).

## Folder Structure
```{r}
.
├── data
│   ├── 0604d3e3-a7dc-4da6-824c-e252969ef14d_Series - Metadata.csv
│   ├── Agrofood_co2_emission.csv
│   ├── aqi.csv
│   ├── area_sa.csv
│   ├── area.zip
│   ├── daily_bang_aqi.zip
│   ├── Dhaka_PM2.5_2016.csv
│   ├── Dhaka_PM2.5_2017.csv
│   ├── Dhaka_PM2.5_2018.csv
│   ├── Dhaka_PM2.5_2019.csv
│   ├── Dhaka_PM2.5_2020.csv
│   ├── Dhaka_PM2.5_2021.csv
│   ├── Dhaka_PM2.5_2022.csv
│   ├── e4aeb3ac-c5d5-44ca-a547-8c4d6f3160a9_Series - Metadata.csv
│   ├── Metadata_Country_API_AG.LND.AGRI.K2_DS2_en_csv_v2_5995315.csv
│   ├── Metadata_Indicator_API_AG.LND.AGRI.K2_DS2_en_csv_v2_5995315.csv
│   ├── project_data.zip
│   ├── south_asia_aqi.zip
│   └── total_cultivable_area.csv
├── README.md
├── south_asia_air.qmd
└── southasia_aqi.Rproj
```

## Conclusion

The project aims to provide insights into the impact of crop burning on air quality in South Asia, offering a foundation for further analysis and potential interventions.

