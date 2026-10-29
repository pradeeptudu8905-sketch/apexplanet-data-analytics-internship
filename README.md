# Netflix  Data Analysis 

**Analyzing Netflix content distribution, ratings, country-wise contributions, and content addition trends using Python.**

##  Project Overview

This project focuses on Exploratory Data Analysis (EDA) of a Netflix titles dataset to identify patterns in content types, ratings, countries, release years, and catalogue additions.

I completed this project during my internship at **Appex Planet**, where I applied Python-based data analysis techniques to explore the dataset, engineer features, and communicate findings through visualizations.

##  Internship Details

- **Organization:** Appex Planet
- **Project:** Netflix Exploratory Data Analysis (EDA)
- **Domain:** Data Analytics
- **Role:** Data Analytics Intern 

##  Dataset

- **Dataset:** `netflix_cleaned.csv`
- **Total Records:** 8,804
- **Original Columns:** 12
- **Content Types:** Movies and TV Shows

##  Tools & Technologies

- **Python** — Data analysis
- **Pandas & NumPy** — Data manipulation
- **Matplotlib & Seaborn** — Data visualization
- **Jupyter Notebook** — Analysis environment

##  Analysis Performed

- Inspected data types, missing values, and duplicate records.
- Created features such as `year_added`, `month_added`, `content_age_when_added`, `num_genres`, `primary_genre`, and `is_movie`.
- Analyzed content types and ratings.
- Explored country-wise content distribution.
- Examined yearly and monthly content addition trends.
- Investigated relationships between selected numerical features.
- Identified directors with the highest title counts.

##  Key Findings

### 1. Movies vs. TV Shows

| Content Type | Titles | Percentage |
|---|---:|---:|
| Movies | 6,128 | 69.6% |
| TV Shows | 2,676 | 30.4% |
| **Total** | **8,804** | **100%** |

Movies account for the majority of titles in the analyzed dataset.

### 2. Content Ratings

| Rating | Number of Titles |
|---|---:|
| TV-MA | 3,207 |
| TV-14 | 2,160 |
| TV-PG | 863 |

TV-MA is the most frequent rating, followed by TV-14.

### 3. Country Distribution

| Country Entry | Number of Titles |
|---|---:|
| United States | 2,815 |
| India | 972 |
| Unknown | 831 |
| United Kingdom | 419 |

The United States has the highest country-entry count, with India also prominently represented.



### 4. Content Addition Trends

Yearly and monthly analysis was used to explore changes in the number of titles added to the catalogue.

## Business Insights

- Movies represent approximately 69.6% of the dataset.
- TV-MA and TV-14 are the most frequent content ratings.
- The United States and India are prominent in the country entries.
- Combining catalogue data with viewership, revenue, and engagement metrics could provide deeper business insights.

##  Visualizations

- Content type and rating distributions
- Release-year and content-age plots
- Country distribution bar chart
- Scatterplots for feature relationships
- Correlation heatmap and pairplot
- Yearly and monthly content addition charts
- Top directors by title count

##  Limitations

- Some records contain `"Unknown"` values.
- Multi-country entries were not split into individual countries.
- Movie runtime and TV show season counts use different units.
- The dataset does not include actual viewership, revenue, or audience engagement metrics.
- Findings describe the analyzed dataset, not Netflix's current business performance.



##  Conclusion

This internship project at **Appex Planet** provided practical experience in data inspection, feature engineering, exploratory data analysis, aggregation, correlation analysis, and data visualization.

The analysis identified patterns in Netflix's content distribution, ratings, country entries, and catalogue additions. These findings demonstrate how exploratory data analysis can help turn raw data into useful observations.

---

**Author:** Pradeep Tudu  
**Organization:** Appex Planet  
**Project:** Netflix Exploratory Data Analysis (EDA)  
**Technologies:** Python, Pandas, Matplotlib, Seaborn