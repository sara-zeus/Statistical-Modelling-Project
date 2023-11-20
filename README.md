# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
This project involves applying Python skills to handle data from APIs, clean and transform it, perform exploratory data analysis, build statistical models, and present findings effectively.

## Process

The main processes involved in the project, outlined in bullet points:

1. **Accessing data using APIs**
2. **Cleaning and transforming data using Python**
3. **Loading data into a database using Python**
4. **Performing Exploratory Data Analysis (EDA) with statistics and visualizations**
5. **Identifying trends and patterns in data using statistical models**
6. **Interpreting the results obtained from the statistical models**
7. **Creating a README.md file for project overview**
8. **Completing four Jupyter notebooks:** 
   - `city_bikes.ipynb`
   - `yelp_foursquareEDA.ipynb`
   - `joining_data.ipynb`
   - `model_building.ipynb`
9. **Structuring a concise presentation covering:**
   - Project flow
   - Results demonstration
   - Regression model explanation
   - Model outputs
   - Challenges faced
   - Potential improvements with more time.



## Results
### Bike Availability vs. Ratings
- No correlation found between the number of bikes available at a location and the rating of that point of interest.

### Price and Review Counts
- Higher-rated restaurants had higher review counts, and more bikes were available where prices were lower.

### Correlation Analysis
- No significant linear relationship found between the number of bikes available and the rating.
- Similarly, no notable linear relationship found between 'categories' and 'rating' based on the correlation analysis.

### R-squared Values
- Close to zero, indicating almost no relationship between the number of available bikes and either rating or review count.

### Coefficients and Significance
- Non-significant coefficients (p-value > 0.05) suggest no meaningful linear connection between the number of available bikes and either rating or review count.

____________________________________________________________________________________________________________________________________________________________________________________________________
- All in all Even without a correlation between bikes available and ratings, constructing an ML model for bike availability is plausible by exploring other influential features. Consider leveraging various models and feature engineering techniques to capture complex relationships beyond linear correlations, refining the model iteratively based on evaluation metrics and domain expertise to improve predictive accuracy.



## Challenges 
### Correlation Difficulty
- Difficulty in establishing a meaningful correlation between bike availability and ratings or review counts.

### Interpreting Coefficients
- Understanding and interpreting the coefficients and p-values in the context of the relationships analyzed.

## Future Goals
- Exploring more advanced statistical techniques,to see if there are potential relationships. 



