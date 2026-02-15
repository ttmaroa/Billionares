# Billionares

## Data Loading and Initial Exploration:

Loaded the 'Billionaires Statistics Dataset Raw - Copy of Data.csv' into a pandas DataFrame. 
Performed initial inspection of the dataset (e.g., tt.head(), tt.columns) to understand its structure and available features.

## Data Cleaning and Preprocessing:

Dropped irrelevant columns such as firstName, lastName, birthYear, birthMonth, birthDay, and Current to streamline the dataset for analysis. Extracted the birth year from the 'Year' column and calculated the age of each billionaire (assuming a current_year for age calculation).

## Exploratory Data Analysis (EDA):

-Industries Analysis: Identified and visualized the industries with the highest number of billionaires using value_counts() and a bar chart.

-Country Analysis: Determined the countries with the most billionaires, displaying the top contenders.

-Country-Specific Industry Deep Dive: Explored and listed the top industries for billionaires within the leading countries (e.g., United States, China, United Kingdom, Germany, India).

-Age Distribution: Visualized the age distribution of billionaires using a histogram to understand typical age ranges.

-Gender Distribution: Counted and displayed the number of male and female billionaires.

-Wealth Origin Analysis: Compared the total wealth of self-made billionaires against those with inherited wealth, illustrating the distribution with a bar chart.

-Top Billionaires Overview: Identified and displayed the top 14 billionaires by net worth, along with their respective countries and industries, and visualized this using a Plotly bar chart.

-Life Expectancy vs. Billionaire Count: Grouped data by country to calculate the number of billionaires and average life expectancy, providing insights into potential correlations.

## Key Insights & Visualizations:

Summarized findings from industry dominance, geographical distribution, age demographics, and the impact of wealth origin.
Highlighted specific charts used (e.g., bar charts for industries, histograms for age, scatter plot for life expectancy vs. billionaire count) to convey information effectively.

