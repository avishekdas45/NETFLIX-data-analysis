
# 📺 NETFLIX Data Analysis: Business Insights from Global Content Distribution using Python

![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/Netflix_2015_logo.svg/1280px-Netflix_2015_logo.svg.png)

Welcome to the Netflix Data Exploration and Visualization project! 🎉 In this repository, we delve into the world of Netflix to uncover valuable insights from their vast library of movies and TV shows. 
---

## 🔗 Table of Contents
- [About Netflix 🍿](#about-netflix-)
- [Project Overview 📊](#-project-overview-)
- [Data Cleaning 🧹](#-data-cleaning-)
- [Key Insights 🔍](#-key-insights-)
- [Visualizations 🌍](#-visualizations-)
- [Dataset Description 🧩](#-dataset-description-)
- [Technologies Used 🛠](#-technologies-used-)
- [Getting Started 🚀](#-getting-started-)
- [Acknowledgements 🙌](#-acknowledgements-)
- [Contact 📬](#-contact-)

---

## Netflix – More Than Just Streaming 🍿

Step into the world of Netflix, where storytelling meets technology at a global scale. With an ever-growing library of 10,000+ movies and TV shows spanning every imaginable genre and language, Netflix has become more than a platform—it's a cultural phenomenon. As of mid-2021, it proudly serves over 222 million subscribers worldwide, redefining how we consume entertainment. From binge-worthy dramas to mind-bending documentaries, Netflix is the go-to destination for viewers seeking immersive experiences from the comfort of home.

---

## 📊 Project Overview

This project utilizes a publicly available Netflix dataset from [Kaggle](https://www.kaggle.com/shivamb/netflix-shows) to:

- Analyze the type and volume of content added to Netflix over time.
- Identify dominant genres and content types.
- Highlight country-wise contributions to Netflix's catalog.
- Study ratings and their suitability for audiences.
- Visualize content trends across years and categories.

---

## 🧹 Data Cleaning

Performed initial cleaning and preprocessing including:

- Removing duplicates and handling missing values.
- Converting `date_added` to datetime format.
- Extracting year and month from the date field.

---

## 🔍 Key Insights

- **Content Growth:** Notable increase in content between 2014 to 2019, with a peak around 2019.
- **Type Distribution:** Netflix has significantly more movies than TV shows in its catalog.
- **Popular Genres:** Drama and International content dominate across countries.
- **Top Contributing Countries:** The United States leads by far, followed by India and the UK.
- **Target Audience:** TV-MA and TV-14 are the most common ratings, indicating a tilt toward mature audiences.

---

## 🌍 Visualizations

Visuals created using `Matplotlib`, `Seaborn`, and `WordCloud` include:

- Year-wise content addition (bar charts).
- Genre heatmaps.
- Ratings distribution.
- Word cloud from descriptions to identify common themes.
- Country-wise content contribution.
- Time analysis

---

## 🧩 Dataset Description

Some key columns in the dataset:

- `title`: Title of the movie/show
- `director`: Director name(s)
- `cast`: Main actors involved
- `country`: Country of production
- `date_added`: Date the content was added to Netflix
- `release_year`: Year of original release
- `rating`: Age rating (e.g., TV-MA, PG)
- `duration`: Length of movie or number of seasons
- `listed_in`: Genre(s)
- `description`: Summary of the content

---

## 🛠 Technologies Used

| Tool | Purpose |
|------|---------|
| **Python** | Core programming language |
| **Pandas** | Data cleaning & manipulation |
| **Matplotlib / Seaborn** | Data visualization |
| **WordCloud** | Text mining and visualization |
| **Jupyter Notebook** | Interactive data analysis |

---

## 🚀 Getting Started

1. Clone this repository  
   ```bash
   git clone https://github.com/avishekdas45/NETFLIX-data-analysis.git
   ```

2. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Netflix_Insights.ipynb
   ```

3. Run the cells in order to view data analysis and visualizations.

---

## 🙌 Acknowledgements

- Dataset Source: [Netflix Titles on Kaggle](https://www.kaggle.com/shivamb/netflix-shows)

---

## 📬 Contact

**Avishek Das**  
Email: contact.avishek@gmail.com  
GitHub: [avishekdas45](https://github.com/avishekdas45)

---
