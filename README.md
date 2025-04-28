# ev_adoption_rates

# EV Adoption Rates: Cluster and Regression Analysis

## Project Overview

The widespread adoption of electric vehicles (EVs) represents a significant step toward reducing greenhouse gas emissions and achieving long-term sustainability goals. As governments and private stakeholders invest in supporting infrastructure and policy incentives, it is essential to understand the demographic, economic, and infrastructural factors that influence EV adoption at the regional level. This project analyzes EV adoption patterns across Washington State’s counties using both cluster and regression analysis.
 
## Methodology

* **Cluster Analysis**: Counties were grouped based on average EV age, charging station density, and EV adoption rates, revealing four distinct clusters with unique demographic and economic characteristics.

* **Regression Analysis**: An Ordinary Least Squares (OLS) regression was conducted to quantify the relationships between EV adoption and variables such as income, education, age, race, creditworthiness, fuel type, electric range, and vehicle type.

## Key Findings

* **Urban Advantage**: Urban counties with higher median household incomes, higher percentage of the population with at least a college degree, and population densities showed the highest EV adoption rates, even without the highest charging station densities.

* **Rural Challenges**: Rural counties with lower income levels, older populations, and lower levels of education showed minimal adoption, despite sometimes having relatively dense charging infrastructure.

* **Infrastructure vs. Socioeconomics**: Charging station density was not a statistically significant predictor of EV adoption, highlighting that infrastructure alone does not drive adoption rates. Socioeconomic factors, particularly income, education, and creditworthiness, play a more important role.

## Recommendations

* **Policy Focus**: Governments should prioritize investments in suburban areas (e.g., Cluster 1), where favorable demographics and moderate EV adoption indicate strong growth potential. In rural areas (Clusters 0 and 3), efforts should focus on public education campaigns and financial assistance programs to address underlying socioeconomic barriers.

* **Manufacturer Strategy**: EV manufacturers should continue targeting urban counties (Cluster 2) for premium offerings, while focusing on affordable models and community engagement in suburban areas (Cluster 1) to stimulate adoption.

## Limitations

* The analysis is based on county-level averages, which may overlook intra-county variations.

* The regression model included data from 36 counties, potentially affecting the statistical reliability of some variables.

* Local grants and incentives were not included in the analysis, which could significantly impact EV adoption rates.

## Future Work

* Incorporate more detailed data, potentially at the zip-code level, to capture localized trends.

* Include data on local grants and incentives to explore their influence on EV adoption.

* Compare findings with other states with high EV adoption rates, such as California and Florida, to identify effective strategies for increasing adoption.

