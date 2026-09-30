[README (1).md](https://github.com/user-attachments/files/32847626/README.1.md)
# Netflix_EDA_Visualization

**Exploratory Data Analysis & Visualization of Netflix Titles**

**Author:** Sabyasachi

## About
Exploratory analysis and visualization of the Netflix Movies and TV Shows dataset (8,807 titles), covering content type split, growth over time, top producing countries, genres, ratings, and movie/TV duration.

## Dataset
`netflix_titles.csv` — Netflix Movies and TV Shows dataset (Kaggle).

## Key Findings
- The catalog is split roughly **70% Movies (6,131) vs 30% TV Shows (2,676)**.
- Content additions to Netflix **peaked in 2019**, after several years of rapid growth.
- The **United States (3,211 titles), India (1,008), and the United Kingdom (628)** are the top three content-producing countries.
- **Dramas** is the single most common primary genre (1,600 titles).
- The average movie runs **~100 minutes** (median 98 minutes).
- Most TV shows are short-lived: the average is under **2 seasons**.
- **TV-MA** is the most common content rating, suggesting the catalog skews toward mature audiences.
- No exact duplicate rows were found, but **`director` (29.9%) and `country` (9.4%) have meaningful missing data**.

## Charts
| Chart | Description |
|---|---|
| `chart_type_split.png` | Movies vs TV Shows count |
| `chart_titles_per_year.png` | Titles added per year |
| `chart_type_trend.png` | Movies vs TV Shows trend over time |
| `chart_top_countries.png` | Top 10 content-producing countries |
| `chart_top_genres.png` | Top 10 genres |
| `chart_ratings.png` | Content rating distribution |
| `chart_movie_duration.png` | Movie duration distribution |
| `chart_genre_country_heatmap.png` | Top genres by top 5 countries |

## Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## How to Run
1. Clone this repo.
2. Install dependencies: `pip install pandas numpy matplotlib seaborn jupyter`
3. Open `Netflix_EDA_Visualization.ipynb` and run all cells.

## Files
- `Netflix_EDA_Visualization.ipynb` — full analysis notebook with charts
- `netflix_titles.csv` — dataset
- `chart_*.png` — exported chart images
- `README.md` — this file
