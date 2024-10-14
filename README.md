# Aerofit Treadmill EDA Case Study

## Overview
This repository contains an exploratory data analysis (EDA) of Aerofit's treadmill product line to help identify customer characteristics for different treadmill products. The analysis aims to provide valuable insights that can improve product recommendations for new customers.

## Business Problem
Aerofit, a leader in fitness equipment, wants to understand the target audience for its treadmill products. Specifically, the market research team is interested in identifying the key customer characteristics for each treadmill product (KP281, KP481, KP781) to make better recommendations.

### Treadmill Products:
- **KP281**: Entry-level, priced at $1,500
- **KP481**: Mid-level, priced at $1,750
- **KP781**: Advanced, priced at $2,500

## Objectives
1. Perform descriptive analytics to create customer profiles for each treadmill product.
2. Construct two-way contingency tables to analyze relationships between customer demographics and product choice.
3. Compute conditional and marginal probabilities to derive insights for better product targeting.

## Dataset
The dataset `aerofit_data.csv` contains the following fields:
- **Product**: Treadmill purchased (KP281, KP481, KP781)
- **Age**: Customer's age (in years)
- **Gender**: Male or Female
- **Education**: Years of education
- **MaritalStatus**: Single or partnered
- **Usage**: Planned treadmill use (times per week)
- **Income**: Annual income (in USD)
- **Fitness**: Self-rated fitness level (1 to 5 scale)
- **Miles**: Expected weekly miles on the treadmill

## Analysis Steps
1. **Data Preprocessing**: Cleaning and preparing the data for analysis.
2. **Descriptive Analytics**: Analyzing customer demographics across treadmill products.
3. **Contingency Tables**: Creating tables to explore relationships between product choice and customer characteristics.
4. **Probability Analysis**: Calculating conditional and marginal probabilities to interpret customer behavior patterns.

## Tools and Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn (for visualizations)

## Conclusion
This analysis provides insights into the customer base for each treadmill product, aiding Aerofit in offering targeted product recommendations and improving marketing strategies.

## Author
- Abhinav Shandilya

