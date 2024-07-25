# IMDB_DATA_ANALYSIS BY EXCEL

## Description
This project involves an in-depth analysis of IMDB movie data using Excel. The analysis includes data cleaning, creating new calculated columns, generating pivot tables, and visualizing the findings with charts.

## Data Cleaning
To ensure the dataset is clean and ready for analysis:

1. **Remove Duplicates:**.
    - There's no duplicates in the dataset
2. **Handle Missing Values:**
    - Handle NULL values in 2 columns: `Language` by replace them by 'English'  and `Plot_keywords` by replace them by movie_title.
3. **Remove Special Character:**
    - Remove special char `Â` from column `movie_title`

## New Calculated Column
To add a new calculated column to your dataset:

1. **Create a New Column (Profits):**
    - Create a new column named `Profits` by calculating the difference between the `gross` and `budget` columns.
2. **Create a New Column (Movie Success?):**
    - Create a new column named `Movie Success?` to check if the movie `success` or `failed` by check if profits is positive or negative
3. **Create a New Column (Decate):**
    - Create a new column named `Decate` to decate the title-years.


## Pivot Tables
Generate pivot tables to answer the following questions:

1. **Total Gross by Genre**
    - Create a pivot table to Sum the gross for each genre.
2. **Average IMDB Score by Director**
    - Create a pivot table to find the average imdb_score for each director_name.
3. **Total Profit by Country**
    - Create a pivot table to sum the profit for each country.
4. **Number of Movies per Year**
    - Create a pivot table to count the number of movies released each title_year.

## Visualization
Create charts to visualize the analysis:

1. **Bar Chart for Total Gross by Genre**
    - use a bar chart to show the total gross revenue for each genre.
    ![total gross by genre](/images/image.png)
2. **Line Chart for Number of Movies per Year**
    - use a line chart to show the trend in the number of movies produced over the years.
    ![number of movie per year](/images/image-1.png)
3. **Average IMDB Score by Director**
    - Use a chart to show the average IMDB scores for different directors.
    ![average imdb_score](/images/image-2.png)

## Contact
Created by [KHOLOD_SADEK] - feel free to contact me at [kholodsadek555@gmail.com].
