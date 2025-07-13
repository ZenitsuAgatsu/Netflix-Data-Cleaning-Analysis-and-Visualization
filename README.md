#  Netflix Data Analysis and Visualization

This project explores and analyzes Netflix's dataset using Python. The goal is to uncover insights about Netflix's content library through data cleaning, exploratory data analysis (EDA), and visualizations.

---

##  Project Objectives

- Clean and preprocess Netflix data
- Perform Exploratory Data Analysis (EDA)
- Visualize trends in content types, genres, countries, and more
- Derive insights into Netflix’s catalog such as:
  - Movie vs TV Show trends
  - Most common genres
  - Country-specific content trends
  - Kids content distribution
  - Genre evolution over years

---

##  Dataset

- 📄 `netflix1.csv`
- The dataset contains information about movies and TV shows available on Netflix including:
  - `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, and `description`.

---

##  Data Cleaning

- Removed duplicates
- Handled missing values (e.g. in rating, director, country)
- Converted date columns to datetime
- Cleaned whitespace and inconsistent formatting

---

##  Exploratory Data Analysis

- Distribution of Movies vs TV Shows
- Most popular genres globally and by country (e.g. USA, India)
- Content trends by year and month
- Duration analysis of movies
- Ratings and kids content breakdown

---

##  Visualizations

- Bar plots, pie charts, line charts, histograms, and word clouds using:
  - `matplotlib`, `seaborn`, and `wordcloud`

Example visualizations:
- 📈 Movies vs TV Shows Over Time  
- 🌎 Top Countries by Content  
- 🎭 Genre Popularity  
- 🧒 Kids Content Distribution  
- 📅 Genre Trends Over Years  

---

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook

---

## Key Insights

- Netflix's content is dominated by movies, but TV shows are growing.
- USA and India contribute the highest number of titles.
- Most content falls under Drama, International Movies, and Comedy.
- Kids' content has distinct rating distributions (TV-Y, TV-Y7).
- Genre preferences have evolved over the years, with increasing diversity.
