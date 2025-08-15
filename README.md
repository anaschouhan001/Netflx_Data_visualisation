# Netflx_Data_visualisation
This project analyzes and visualizes Netflix’s public dataset (netflix_titles.csv) using Python, Pandas, and Matplotlib. The goal is to gain insights into Netflix’s content library by exploring types of shows, ratings, durations, release trends, and country-wise distributions.
# 🎬 Netflix Data Visualization

This project analyzes and visualizes Netflix's movies and TV shows dataset using Python.  
It provides insights into trends such as content type distribution, ratings, release years, durations, and top content-producing countries.

---

## 📌 Table of Contents
- [About the Project](#-about-the-project)
- [Dataset](#-dataset)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Generated Visualizations](#-generated-visualizations)
- [Insights](#-insights)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🔍 About the Project
This project uses the **Netflix Titles Dataset** to create meaningful visualizations that answer:
- How many movies vs. TV shows are on Netflix?
- Which countries produce the most Netflix content?
- What is the distribution of movie durations?
- How has Netflix's content grown over the years?
- What is the percentage share of different ratings?

The results are displayed in bar charts, pie charts, histograms, scatter plots, and line plots.

---

## 📂 Dataset
The dataset used: **Netflix Movies and TV Shows** from Kaggle  
🔗 [Netflix Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

**Key Columns:**
- `type` — Movie or TV Show
- `title` — Name of the show/movie
- `country` — Country of origin
- `release_year` — Year of release
- `rating` — Content rating (e.g., PG, TV-MA)
- `duration` — Duration of the show/movie

---

## ✨ Features
- Data cleaning (removing missing values for key fields)
- Visualization of:
  - Movies vs. TV Shows count
  - Ratings percentage distribution
  - Movie duration distribution
  - Release year trends
  - Top 10 countries by content count
  - Yearly comparison of Movies and TV Shows
- Saves all charts as `.png` files

---

## 🛠 Technologies Used
- **Python**
- **Pandas** – Data cleaning & manipulation
- **Matplotlib** – Data visualization

---

## 📥 Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/netflix-data-visualization.git
   cd netflix-data-visualization
   Install dependencies

pip install pandas matplotlib


Download dataset
Get netflix_titles.csv or netflix_titles.csv.zip from Kaggle and place it in the project folder.

🚀 Usage

Run the Python script:

python netflix_data.py


This will:

Clean the data

Generate visualizations

Save charts as PNG images in the project folder

Display the charts one by one

📊 Generated Visualizations

movies_vs_tvshows.png – Bar chart: Movies vs TV Shows count

content_rating_pie.png – Pie chart: Percentage of each content rating

movie_duration_histogram.png – Histogram: Movie duration distribution

release_year_scatter.png – Scatter plot: Release year vs number of shows

top10_countries.png – Bar chart: Top 10 countries by number of shows

movies_tv_shows_comparison.png – Line plot: Yearly comparison of Movies & TV Shows

💡 Insights

Netflix has more movies than TV shows.

The majority of Netflix content has been released after 2010.

The USA and India are top content producers.

Drama and International content dominate the genres.

Most movies have a duration between 80–120 minutes.

🤝 Contributing

Fork the project

Create a new branch (feature/YourFeatureName)

Commit your changes

Push to your branch and open a Pull Request

📜 License

This project is licensed under the MIT License.


---

If you want, I can **add example chart images directly into the README** so your GitHub page looks more visual and appealing when someone visits. That would make recruiters notice it immediately.  

Do you want me to make that version with chart previews?
