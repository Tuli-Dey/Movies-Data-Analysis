# 🎬 Movies Dataset Analysis Dashboard

> An interactive **Movies Dataset Analysis Dashboard** built using **Microsoft Excel** to explore movie industry trends, financial performance, audience ratings & Box Office Analysis. The goal is to extract meaningful insights and visualize patterns in the movie industry using data-driven techniques.

---
# 1. Project Title

> Movies Dataset Analysis and Visualization using Microsoft Excel.

---
# 2. Project Overview

> This project focuses on analyzing a structured movies and TV content dataset to uncover key trends in the entertainment industry. The dataset includes detailed information such as content type (Movies, TV Series, Stand-up), genres, release years, duration, IMDb ratings, production budgets, box office revenue, and platform availability.

The objective of this analysis is to transform raw data into meaningful insights by examining patterns in audience preferences, genre performance, and financial outcomes. The project highlights how factors like content type, budget, and platform distribution (including Netflix Originals) influence ratings and revenue generation.

Through interactive dashboards and data visualization techniques (primarily using Microsoft Excel), this project enables a clear comparison of different entertainment categories, helping identify high-performing genres, profitable content strategies, and evolving industry trends over time.

Overall, this project demonstrates the practical application of data analytics in the media and entertainment domain, supporting data-driven decision-making for content creation, investment, and distribution strategies.

---
# 3. File Details

## Raw Data
- **Movies.csv** - Raw Dataset before cleaning.
## Cleaned Data
- **Cleaned Movies.csv** - Dataset after cleaning process.
## Pivot Analysis
- **Movies Pivot Table Calculation1.xlsx** - Pivot Analysis based on Content type (Movies, TV Series, Stand-up Comedy, etc.)
- **Movies Pivot Table Calculation2.xlsx** - Pivot Analysis based on country_of_origin (Canada, France, India, etc.)
## Dashboard
- **Dashboard.png** – Screenshot of the final Excel dashboard.

---

# 4. Data Dictionary

Below are the description of each Columns used in the dataset.

| Column Name       | Data Type| Description                                      |
|-------------------|----------|--------------------------------------------------|
| id                | Integer  | Unique values for each column                    |
| title             | Text     | Name of the Documentary or Movies                |
| content_type      | Text     | Category of the content (Movie, TV Series, etc.) |
| genre_primary     | Text     | Primary genre classification                     |
| genre_secondary   | Text     | Additional genre classification if applicable    |
| release_year      | Integer  | Year when the content was released               |
| duration_minutes  | Integer  | Total runtime in minutes                         |
| rating            | Text     | Certification rating (PG-13, R, TV-MA, G, etc.)  |
| language          | Text     | languages used in the content                    |
| country_of_origin | Text     | In which Country the content was produced        |
| imdb_rating       | Decimal  | IMDb rating score ranking from 0 to 10           |
| production_budget | Decimal  | Budget for produce the content                   |
| box_office_revenue| Decimal  | Total box office revenue generated               |
| number_of_seasons | Integer  | Number of seasons (for TV series)                |
| number_of_episodes| Integer  | Total episode count (for TV series)              |
| is_netflix_original| Boolean | Indicates if the content is a Netflix original   |
| added_to_platform | Date     | Date when the content was added to the platform  |
| content_warning   | Boolean  | Indicates presence of a content warning          |

---

# 5. Cleaning Notes
Below are the cleaning steps were performed to prepare the dataset into meaningful insights.
- The **movie_id** column originally contained values such as movie_001, movie_002. For cleaning purpose extracted only the unique numeric values.
- Removed **movie_id** column and rename it by **id**.
- Sort the dataset based on the **id** column.

---

# 6. Analytics View
Below are the KPIs used in the Dashboard -

- Total number of content items in the dataset.
- Average runtime of content in minutes.
- Average IMDB rating of content.
- Total production cost.
- Total earning from box office.
- Total seasons for TV series.
- Total episodes for TV series.

Below is the description of the charts used in the dashboard -

- Calculation of content type based on the Total number of content items.
- Calculation of Average runtime of content in minutes over content types.
- Average IMDB rating calculation by content type.
- Calculation of Investment vs Return.
- Country wise financial growth.
- Country wise Investment vs Return.

---

# 7. Dashboard View

<img width="1310" height="494" alt="Dashboard" src="https://github.com/user-attachments/assets/7afde3fa-9996-4112-82b8-655d7bd0afde" />

---

# 8. Analysis Report

This dashboard provides insights into Netflix content performance across multiple dimensions including content type, ratings, duration, and financial metrics.
- The dataset contains **1040 movies** with an average duration of ~80 minutes and an average IMDb rating of **6.2**.
- Total **production investment (~11.56B)** generated **~67.19B revenue**, indicating strong overall profitability.
- **Movies dominate the platform** with the highest content count and contribute the most to total watch time and revenue.
- **TV Series maintain slightly higher audience ratings**, reflecting consistent viewer engagement.
- **Stand-up Comedy shows strong Return On Investment**, delivering good returns with relatively low investment.
- Country-wise analysis shows **revenue concentration in key regions**, suggesting potential for growth in emerging markets.

---

# 9. Conclusion

The analysis indicates that Netflix’s content portfolio is **profit-driven and strategically diversified**, with a clear dominance of movies in both volume and revenue contribution. While **TV series ensure steady user engagement through higher ratings, stand-up comedy emerges as the most cost-efficient category**, delivering strong returns with minimal investment.

Optimizing the content mix by **increasing investment in high-ROI formats and expanding geographically** can further enhance overall performance and long-term growth.
