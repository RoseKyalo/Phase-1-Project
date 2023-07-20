# Movie Industry Analysis

![Image Alt Text](/Images/readme_image.webp)





This repository contains the analysis of the movie industry using "The Numbers Movie Budget" dataset from The Numbers website. The analysis was performed using Python's Pandas DataFrame to explore the popularity and profitability of movies from 1920 to 2020.

## Overview
The movie industry is a dynamic and thriving market that continues to captivate audiences worldwide. To gain insights into this industry, we aimed to address the following key questions:

1. What types of movies are currently performing exceptionally well in terms of popularity and profitability?

2. How has the profitability of movie production evolved over time, from 1920 to 2020?

3. Does the production budget significantly influence the overall profit of movies?

## Data Understanding
The dataset comprises 5782 rows and 6 columns.The columns are as follows:

1. id - Unique identifier for each movie.

2. release_date - Date of movie release.

3. movie - Name of the movie.

4. production_budget - Production budget of the movie.

5. domestic_gross - Domestic gross revenue of the movie.

6. worldwide_gross - Worldwide gross revenue of the movie.

There were no missing values or duplicates in the dataset. To facilitate our analysis, we converted the 'production_budget', 'domestic_gross', and 'worldwide_gross' columns to integer data types and transformed the 'release_date' column to datetime type.

## Key Findings
1. Most movies achieved international profitability, emphasizing the importance of global appeal in production strategy.
   
2. Movies like Avatar, Titanic, Avengers: Infinity War, Star Wars Ep. VII: The Force Awakens, and Jurassic World are excellent examples with broad international appeal.

3. Certain movies, such as Titanic, Jurassic World, and Star Wars Ep.VII: The Force Awakens, succeeded in both domestic and international markets, making them strong candidates for investment or collaboration.
   
4. The movie industry has been consistently profitable since 1920, indicating its enduring nature and resilience.

5. There is a positive correlation between production budget and movie profitability, indicating that higher investments lead to higher returns both domestically and worldwide.
   
## Recommendations
Based on the analysis, we recommend the following:
1. Prioritize producing movies with broad international appeal to tap into global markets.
   
2. Study successful movies like Avatar, Titanic, and Avengers: Infinity War for valuable insights into international appeal.

3. Consider investing in movies that have demonstrated profitability in both domestic and international markets.

4. Embrace the enduring nature of the movie industry and explore opportunities for long-term growth and success.

5. Allocate budgets strategically to maximize profitability and ensure a positive return on investment.

## Conclusion
The movie industry analysis reveals a promising and vibrant market with exciting opportunities for company X. By leveraging global appeal, learning from successful movies, and making prudent budget decisions, company X can position itself for success in this dynamic and ever-evolving industry.

For detailed insights and code implementation, refer to the Jupyter Notebook provided in this repository.

## Dependencies
The analysis was conducted using Python with the following libraries:

1. Pandas
2. Matplotlib
3. Seaborn
   
## Folder Structure

|- data/

    |- tn.movie_budgets_.csv
    
|- analysis/

    |- movie_industry_analysis.ipynb
    
|- visualizations/

    |- scatter_plot.png
    
    |- bar_chart.png

     |- line_plot.png
    
|- README.md

Licensing
The dataset used in this analysis is available under the terms of the provided license from The Numbers website. For more information on the dataset license, please refer to the "data" folder.

Feel free to explore the analysis and contribute to this repository. Happy analyzing!
