# Surprise_housing_Case_Study
### Overview
This project aimed to analyze the factors influencing house prices using a dataset from a housing market. We applied Ridge and Lasso regression models to identify the key features that have the greatest impact on property values. Through this analysis, we gained insights into the most important factors driving house prices and built predictive models to aid in real estate decision-making.

### Key Findings
1. Living Area (GrLivArea):
- The size of the living area emerged as the most significant predictor of house prices in both Ridge and Lasso models. Larger homes consistently command higher sale prices, highlighting the importance of square footage when valuing a property.

2. Overall Quality (OverallQual):
- The overall build quality of a house, particularly homes rated 8 or 9, has a strong positive impact on price. High-quality construction and materials increase a home’s value, making this a crucial factor for both buyers and sellers to consider.

3. Garage Capacity (GarageCars):
- Homes with larger garages (i.e., those that can accommodate more cars) tend to sell for higher prices. This indicates that buyers place a premium on parking and storage space, which can be an important consideration for property upgrades.

4. Neighborhood:
- The neighborhood in which a home is located plays a critical role in determining its price. Homes in sought-after neighborhoods, such as "NridgHt" and "Crawfor," are more valuable, confirming the conventional wisdom that location is key in real estate.

5. Roof Material:
- An unexpected finding from the Lasso model was the importance of roof materials. Homes with certain roof types, such as wood shingles and composite shingles, showed a significant increase in sale price. This suggests that higher-end or unique materials can add value to a home, beyond the typical structural and location-related factors.

### Model Performance
- Both Ridge and Lasso regression models performed well in predicting house prices, with the following highlights:

- Ridge Regression identified the most significant numerical features (like living area, 1st floor square footage, and garage capacity) while handling multicollinearity.

- Lasso Regression was effective in feature selection, reducing the number of features to the most important ones, and identifying additional categorical features like roof material that significantly affect prices.

### Conclusion
The project demonstrates the value of using regression techniques to understand the factors influencing house prices. Key features such as living area, overall quality, garage capacity, and neighborhood are strong predictors, while roof materials emerged as an interesting secondary factor. These insights can help real estate professionals, homeowners, and buyers make informed decisions when evaluating properties or planning home improvements.

### Future Work
In future iterations of this analysis, additional modeling techniques such as Random Forest or Gradient Boosting could be explored to further improve predictive accuracy. Additionally, incorporating more features related to market conditions (e.g., interest rates, economic data) could provide a more comprehensive understanding of the factors influencing house prices.
The project demonstrates the value of using regression techniques to understand the factors influencing house prices. Key features such as living area, overall quality, garage capacity, and neighborhood are strong predictors, while roof materials emerged as an interesting secondary factor. These insights can help real estate professionals, homeowners, and buyers make informed decisions when evaluating properties or planning home improvements.

Future Work
In future iterations of this analysis, additional modeling techniques such as Random Forest or Gradient Boosting could be explored to further improve predictive accuracy. Additionally, incorporating more features related to market conditions (e.g., interest rates, economic data) could provide a more comprehensive understanding of the factors influencing house prices.
