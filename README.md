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
- **Movies.xlsx** - Raw Dataset before cleaning.
## Cleaned Data
- **Cleaned Movies.xlsx** - Dataset after cleaning process.
## Pivot Analysis
- **Pivot Analysis1.xlsx** - Pivot Analysis based on Content type (Movies, TV Series, Stand-up Comedy, etc.)
- **Pivot Analysis2.xlsx** - Pivot Analysis based on country_of_origin (Canada, France, India, etc.)
## Dashboard
- **Dashboard_image.png** – Screenshot of the final Excel dashboard.

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

