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



# Results

## Bike Availability vs. Ratings

It turns out there's no clear link between the number of bikes available at a location and the ratings of those places.

## R-squared Values

Those values were pretty close to zero, suggesting there's hardly any relationship between the number of bikes available and the ratings or review counts.

## Coefficients and Significance

The coefficients weren't significant enough (p-value > 0.05), indicating no solid linear connection between the number of bikes available and the ratings or reviews.

## Challenges and Things I Would Do Differently: Things to Consider

Difficulty in establishing a meaningful correlation between bike availability and ratings or review counts.

I also pulled data from the bike API at night, which might've skewed my results a bit. In the future, I'd like to try out different times of day and see how that affects the results.

Despite the absence of a direct connection between bike availability and ratings, it's still feasible to build a Machine Learning model for bike availability. Exploring different influential features, using various models, and refining the model iteratively based on evaluations and expertise can capture the complex relationships beyond just linear correlations, improving predictive accuracy.

For example, I could try out different models, such as Random Forests, and see how they perform. I could also add more features to the dataset, such as the number of bike racks available at each location. I could also try out different ways of modeling, tweaking features, and adding more to the dataset. I believe there's a whole world of intricate connections beyond the obvious ones. I'm aiming to fine-tune those models, bringing in expert knowledge to make them even better.

## Conclusion

During this project, I really dove into understanding how bike availability relates to the different characteristics of Points of Interest (POIs) in a specific area. Despite digging deep, analyzing data, and building models, I couldn't find a clear connection between the number of available bikes and the ratings or reviews of these places. The tough part was trying to pin down a definite link, and it made me realize just how complex the data I collected was. Especially since it was specific to nighttime in Paris, it might've swayed my findings a bit. There's definitely more to explore there. But you know what? This whole journey showed me just how crucial it is to really dig into data and understand those models. Even though I couldn't find a direct, simple relationship, it was eye-opening to see how many factors play into predicting bike availability. Looking ahead, I'm excited to try out different ways of modeling, tweaking features, and adding more to the dataset. I believe there's a whole world of intricate connections beyond the obvious ones. I'm aiming to fine-tune those models, bringing in expert knowledge to make them even better.
