# Movie Industry Analysis

An exploratory data analysis project examining factors that influence movie success, with a focus on understanding correlations between budget, gross revenue, ratings, and other key metrics.

## Overview

This project analyzes a dataset of movies to uncover insights about the film industry. The analysis explores relationships between various features like budget, gross earnings, ratings, and production companies to identify what factors contribute most to a movie's financial success.

## Key Findings

- **Budget vs Gross Revenue**: Strong positive correlation between production budget and box office earnings
- **Top Production Companies**: Identified the highest-grossing studios based on cumulative revenue
- **Rating Impact**: Analyzed how movie ratings (G, PG, PG-13, R) relate to gross earnings
- **Score vs Revenue**: Investigated whether higher critic/audience scores lead to better financial performance

## Technologies Used

- **Python 3**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization

## Analysis Performed

1. **Data Cleaning**
   - Handled missing values
   - Removed duplicate entries
   - Verified and corrected data types

2. **Exploratory Data Analysis**
   - Distribution analysis of key variables
   - Outlier detection using box plots
   - Scatter plots for relationship visualization

3. **Correlation Analysis**
   - Pearson, Kendall, and Spearman correlation methods
   - Correlation heatmaps for numeric and categorical features
   - Identified strong correlation pairs (|r| > 0.5)

4. **Company Performance Analysis**
   - Ranked production companies by total gross revenue
   - Year-over-year performance breakdown

## Dataset

The dataset contains movie information including:
- Movie title and release date
- Budget and gross revenue
- Ratings and scores
- Production company
- Genre and other metadata

## How to Run

1. Clone this repository
2. Ensure you have Python 3.x installed
3. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Open `Movie Portfolio Project.ipynb` in Jupyter Notebook or VS Code
5. Update the file path in the first cell to point to your local `movies.csv` file
6. Run all cells

## Project Structure

```
├── Movie Portfolio Project.ipynb   # Main analysis notebook
├── movies.csv                       # Dataset (not included)
└── README.md                        # Project documentation
```

## Future Improvements

- Add genre-based analysis
- Include time series analysis of movie trends
- Build predictive models for gross revenue
- Incorporate additional data sources (streaming, international box office)

## License

This project is open source and available for educational purposes.
