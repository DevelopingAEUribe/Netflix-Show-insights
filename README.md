# Netflix-Show-insights
Enriched Netflix data with IMDb ratings and genres to uncover viewer trends. Explored genre popularity, top-rated shows, and runtime patterns using Python, Pandas, and Seaborn.

##  Objectives

- Integrate Netflix and IMDb datasets to create a rich, unified source of truth.
- Analyze trends in genres, runtime, and viewer ratings.
- Visualize key insights to understand what drives popularity on Netflix.

---

##  Tools & Technologies

- **Python** (Pandas, NumPy)
- **IMDb Datasets** (title.basics.tsv.gz, title.ratings.tsv.gz)
- **Netflix Titles Dataset** (CSV)
- **Matplotlib & Seaborn** for visualization
- **Google Colab** for development

---

## Data Sources

-  **Netflix Titles**: [Kaggle Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
-  **IMDb Datasets**: [IMDb Official Datasets](https://www.imdb.com/interfaces/)

---

## 🔄 Data Preparation

- Cleaned and standardized column names and types
- Filtered IMDb data to include only movies and TV series
- Handled missing runtime, release year, and genre values
- Merged Netflix and IMDb data on `title` and `release_year`

---

##  Key Insights

###  Top-Rated Titles on Netflix
- Displayed the top 10 highest-rated Netflix titles (with >1000 IMDb votes)

###  IMDb Rating Distribution
- Most Netflix content sits between **6.0 and 7.5**, with a few high outliers

###  Genre Popularity
- Drama and documentary are the most common genres
- Average IMDb ratings vary by genre, with some niche genres rating higher

###  Runtime Trends
- Action and crime titles tend to have longer runtimes
- Shorter runtimes are common in comedies and documentaries

### Ratings vs Votes
- Titles with more votes tend to have more reliable and slightly higher ratings

---

## Outputs

- Cleaned merged dataset: `netflix_show_insights.csv`
- Visualizations: Matplotlib and Seaborn charts
- Reproducible Google Colab notebook (coming soon)

---

## Sample Visualizations

![Rating vs Votes](images/rating_vs_votes.png)
![Genre Distribution](images/genre_distribution.png)
![Runtime by Genre](images/runtime_by_genre.png)

> You can generate these plots from the notebook using provided code.

---

## Next Steps

- Add sentiment analysis on descriptions
- Cluster shows by genre and rating
- Create a dashboard using Plotly or Streamlit

---

## Acknowledgments

- IMDb for their open data: [https://www.imdb.com/interfaces](https://www.imdb.com/interfaces)
- Netflix dataset from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## Author

**Adam Edwards**  
Data Analyst | Python • SQL • Tableau • Excel  

