# TMDB Movie Dataset Analysis

## Project Overview

This project performs an exploratory data analysis (EDA) on the TMDB (The Movie Database) movie dataset. The main objectives are to understand movie trends over the past 20 years (2004–2023), analyze key performance indicators (KPIs) like ROI (Return on Investment) and profit, and evaluate how major production companies and genres have performed over this period. 

## Dataset Information

The dataset used in this analysis is based on TMDB's movie data, which includes information on:
- Movie titles
- Genres
- Release dates
- Budget and revenue figures
- Production companies
- Popularity scores
- ROI (calculated as revenue divided by budget)
- Other metadata

The dataset has been filtered to include movies released between **January 2004 and December 2023**, and those with budgets greater than **$15 million** to focus on commercially significant films.

## Key Objectives

1. **Exploratory Data Analysis (EDA)**:
    - Generate insights into movie production trends, budget, and revenue distribution.
    - Investigate the relationship between popularity, ROI, and profit.

2. **KPI Calculation**:
    - **ROI (Return on Investment)**: Used to evaluate the success of a movie based on the revenue it generated relative to its budget.
    - **Profit**: Simple measure of the profitability of a movie, calculated as revenue minus budget.
  
3. **Insights on Popular Production Companies and Genres**:
    - Frequency analysis of production companies involved in the most profitable movies.
    - Analysis of which genres have been the most successful in recent years.

4. **Company-specific Insights**:
    - Special focus on key players in the industry, like **Universal Pictures**, **Walt Disney Pictures**, and **Marvel Studios**. 

## Project Files

- `TMDB_movie_dataset_v11.csv`: The original dataset used for analysis.
- `analysis_script.ipynb`: The Jupyter notebook containing the code and visualizations.
- `README.md`: This documentation file explaining the project's scope and workflow.

## Visualizations and Key Findings

1. **Budget Distribution**:
    - Analysis of movie budget distribution showed a **bimodal distribution**—most movies either fall into a low-budget independent category or a high-budget commercial category.
    - A **log10 transformation** was applied to better visualize the spread of budgets.

2. **Movies Released Per Year**:
    - There has been a **steady decline** in high-budget movie releases since 2004, with a notable dip in 2020 due to the **COVID-19 pandemic**.
    - **Post-pandemic recovery** is visible in 2023, both in terms of the number of movies released and the investments made.

3. **Most Profitable Movies**:
    - Movies with the **highest ROI** tend to come from a range of genres, including **adventure, action, and fantasy**.
    - **Independent films** often rank higher in ROI, while **blockbusters** tend to dominate in total profit.

4. **Top Production Companies and Genres**:
    - **Universal Pictures** and **Walt Disney Studios** are some of the most frequent production companies behind the top profitable movies.
    - **Adventure** and **Fantasy** are among the most popular genres for commercial success.

## Dependencies

The project was developed using **Python 3.x**. The following Python libraries are required to run the analysis:

- `pandas`: Data manipulation and analysis.
- `numpy`: Numerical operations.
- `matplotlib`: Data visualization.
- `seaborn`: Advanced visualization for plots.
- `datetime`: Date manipulation.

To install these libraries, run:

```bash
pip install pandas numpy matplotlib seaborn
```

## Running the Analysis

1. Ensure you have the necessary Python dependencies installed.
2. Clone this repository and download the dataset (`TMDB_movie_dataset_v11.csv`).
3. Run the Jupyter notebook `analysis_script.ipynb` in your preferred environment (JupyterLab, VSCode, etc.).

## Key Visualizations

The analysis provides various insights through visualizations, such as:
- **Histogram and boxplots** to understand budget distribution.
- **Line plots** to show trends in the number of movies produced, profit, and popularity per year.
- **Bar charts** for the frequency analysis of production companies and genres.

## Conclusion

This analysis offers a comprehensive look at the commercial movie landscape over the last 20 years, highlighting significant trends in production, profitability, and industry players. It reveals how the movie business has evolved, especially after the challenges of the COVID-19 pandemic, and provides actionable insights into what genres and companies have dominated the box office.

## Author

This project was carried out by Jay Chidirala.

## License

This project is licensed under the [MIT License](LICENSE).

