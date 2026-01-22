## Project Overview
This project showcases a complete data cleaning, transformation, and exploratory analysis workflow using Power Query and Power BI, applied to Netflix content data to derive meaningful insights.

## Data Cleaning & Transformation
The dataset contained significant gaps and inconsistent formatting. To improve data quality and prepare the dataset for analysis, Power Query was used to implement a robust ETL (Extract, Transform, Load) process.
#### 1. Handling Missing Values:
- Over 2,600 missing values in the Director, Cast, and Country columns were replaced with "Unknown" to preserve the dataset for full-volume analysis.

#### 2. Date Standardization:
- The Date Added column was converted to a proper datetime format, enabling extraction of the year content was added to Netflix.

#### 3. Duration Cleaning:
- Numeric values were extracted from the Duration column E.g Minutes for Movies and Number of seasons for TV Shows.
This enabled accurate statistical analysis and comparison.

### 4. Data Type Corrections:
- Ensured all columns were assigned appropriate data types to support reliable analysis.

## Key Insights
- Content Growth and Production Peak:
Netflix experienced a rapid increase in content additions beginning around 2014, coinciding with its transition from a content distributor to a major producer of original content. This growth peaked in 2019, with 2,016 titles added, marking a high-production phase before global production challenges emerged in 2020–2021. Despite these disruptions, Netflix maintained a strong expansion strategy, adding over 1,400 titles in 2021.

- Content Type Distribution:
Movies dominate Netflix’s catalog, with 5,655 Movies compared to 2,627 TV Shows, reflecting a strategic emphasis on feature-length content.

- Content Duration Strategy:
The average movie duration of approximately 100 minutes suggests a deliberate focus on standard feature-length productions that align with global viewing preferences.

-  Geographical Distribution and Global Expansion:
 The United States, India, and the United Kingdom are the top contributors to Netflix’s content library. The United States leads due to its established entertainment industry and heavy investment in original productions. In addition, the strong presence of Japan and South Korea among top contributing countries highlights Netflix’s successful expansion into Asian markets, particularly through Anime and K-Dramas, which have become central to its global growth strategy. 

-  Metadata Gaps:
A notable number of titles (808 records) have an "Unknown" country value, indicating opportunities for further data enrichment and improved metadata completeness.

## Tools Used
- Power Query – For data cleaning and transformation
- Power BI – For analysis and visualization

## Conclusion
This project demonstrates the full ETL and analysis workflow using Power Query and Power BI. The dataset was successfully cleaned, transformed, and enriched to support meaningful exploratory analysis. Key findings revealed trends in content growth, content type distribution, duration patterns, and geographical contributions, highlighting Netflix’s strategic expansion and global content strategy.


