# 📊 Manhwa Analysis: A Mini Exploratory Data Project

## 👋 Introduction
This project is a personal initiative to explore and analyze a self-built dataset of action-themed Korean webcomics (*manhwa*) — especially those featuring **murim**, **hunter**, and **fantasy elements**.  
It's part of my ongoing journey to develop skills in **Python for Data Analysis**, covering data wrangling, descriptive statistics, and data visualization.

## 📁 Dataset Overview
- **Source**: Manually curated based on popular titles I’ve read.
- **Total Entries**: 45 manhwa titles
- **Features**:
  - `title`: Name of the manhwa
  - `author`: Author's name
  - `rating`: Personal rating (1–10 scale)
  - `readers`: Estimated number of readers
  - `release_year`: Year of first release
  - `status`: Ongoing or Complete
  - `platform`: Original publishing platform (e.g. Webtoon, KakaoPage)
  - `chapters`: Number of chapters released

## 🧼 Workflow
1. **Import Libraries**  
   `pandas`, `matplotlib`, `seaborn`

2. **Load Dataset**  
   Read `.csv` file using UTF-8-SIG encoding to handle special characters.

3. **Data Cleaning**
   - Normalize column names
   - Check for missing values or duplicates

4. **Preview & Description**
   - `.head()` and `.shape()` used to inspect structure
   - Descriptive statistics to summarize numerical fields

5. **Visualizations & EDA**
   - Pie chart: Status distribution (Ongoing vs Complete)
   - Line chart: Release trend over years
   - Bar chart: Platform popularity
   - Top 10 charts: Sorted by Rating and Readers
   - Top Authors by Readers

## 🔍 Key Insights
- Most manhwa in this list are **ongoing**, indicating strong reader engagement with serialized works.
- **Solo Leveling** and **Omniscient Reader’s Viewpoint** dominate both in rating and reader count.
- **KakaoPage** and **Naver Webtoon** are the most dominant platforms.
- Titles with high reader counts tend to be published between **2018–2022**, aligning with the manhwa global boom.

## 🤔 Reflections
> This mini project was done entirely from scratch — from building the dataset, analyzing it, and visualizing key patterns.  
> As a beginner in data analytics, this was a fun and motivating way to apply Python on something I genuinely enjoy.  
> I hope to improve my analysis depth and storytelling ability in future projects. Feedback is welcome!

## 📌 Tech Stack
- Python (Jupyter Notebook)
- Pandas
- Matplotlib
- Seaborn
