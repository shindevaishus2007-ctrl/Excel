# 🎬 Netflix Movie and TV Shows (June 2021)

## 🎯Project Objective

The objective of this Netflix Movies and TV Shows Analysis project is to analyze streaming content patterns, audience rating distributions, genre popularity,
and geographic production trends using interactive visualizations. The dashboard aims to help stakeholders track catalog expansion, 
identify top content-producing countries, evaluate content classification (Movies vs. TV Shows), and make data-driven decisions regarding content acquisition and audience targeting.

## 📊Dataset Description
This dataset contains metadata for movies and TV shows available on Netflix. Each row represents a unique title and includes details regarding content type, title, creative team, release metrics, ratings, and genre classifications

## Dataset Columns

| **Column** | **Description** |
|------------| --------------- |
| Show ID | Unique identification number for each Title |
| Type | Classification of the content ( Movie or TV Show )|
| Title | Name of the Movie or TV Show |
| Director | Director(s) involved in the title |
| Cast |  Main actor and actresses featured in the title |
| Country | Country or Countries where the title was produced |
| Date Added | Date on which the title was added to Netflix |
| Release Year | Original release year of the movie or TV show |
| Rating | Content rating classification (e.g., TV-MA, PG-13, TV-14)
| Duration | Length in minutes(for Movies) or number of seasons (for TV show)
| Listed in | Genre categories under which the title is listed |
| Description | A brief summary or synopsis of the title |

## 🧮Calculated Columns

• Year Added-Extracted from the Date Added Field.
• Month Added-Extracted from the Date Added field to track monthly
  addition trends.
• Type Category-Categorized as Movie or TV Show for simplified filtering.
• Duration Numerical-Extracted numeric value for the Duration column (e.g., runtime in minutes or number of seasons)

## 📈Dashboard Features 

## KPI Cards
• Total Titles 
• Total Movies 
• Total TV Shows 
• Total Directors
• Total Countries 
• Average Movie Duration(Minutes)
• Most Frequent Rating
 
## Charts

📈 Monthly Content Addition Trend.

📊 Titles Added vs Release Year.

📊 Total Titles by Genre(Listed in)

🍿  Movies vs TV show Distribution.

🍩 Rating Distribution(TV-MA, TV-14, PG-13,etc.)

📊 Top 10 content Producing.

📍 Movies vs TV Shows by Country.

## Interactive Filters
• Release Year 

• Month Added  

• Country

• Content Type(Movie/TV Show)

• Rating

• Genre(Listed In)

