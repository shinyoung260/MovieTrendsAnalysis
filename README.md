# Movie Ratings and Genre Trends  

## Research Questions  
1. How does movie length influence user ratings by year?  
2. Does the year of release affect genre preference trends?  

## Data Sources  
- **IMDB Dataset**: Movies dataset from the `ggplot2movies` package.  
- **Netflix Originals Dataset**: IMDb scores for Netflix Originals ([Kaggle Dataset](https://www.kaggle.com/datasets/luiscorter/netflix-original-films-imdb-scores)).  

## Data Wrangling  
- Filtered IMDB data for movies with ≥1000 votes and released after 2000.  
- Converted genre columns to long format for analysis.  
- Cleaned and structured Netflix data, extracting years from release dates.  

## Key Steps  
1. **IMDB Trends:**  
   - Analyzed the influence of length on ratings for movies released post-2000.  
   - Highlighted top-rated movies by genre.  

2. **Netflix Trends:**  
   - Explored yearly trends in IMDb scores for Netflix Originals.  

## Tools and Libraries  
- **Languages:** R  
- **Libraries:** `ggplot2`, `tidyr`, `dplyr`, `ggplot2movies` 

