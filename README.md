# Netflix EDA (Exploratory Data Analysis)

This project explores and analyzes a Netflix dataset to uncover insights about the content available on the platform. The dataset includes information such as movie titles, types, release years, durations, countries, and more.

## 📁 Dataset

The dataset used is publicly available and contains metadata about TV Shows and Movies on Netflix.

- Source: [Netflix Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Columns include: `title`, `type`, `release_year`, `duration`, `country`, `rating`, `date_added`, etc.

## 🔍 Objectives

- Clean the dataset and handle missing data.
- Convert and extract useful time-based features.
- Perform univariate and bivariate analysis.
- Visualize trends in content types, durations, release timelines, and countries.

## 🛠️ Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (for interactive analysis)

## 📊 Key Insights

- Distribution of movies vs TV shows.
- Content added over the years and months.
- Top contributing countries.
- Duration patterns and outliers using boxplots.
- Correlation between release year and content duration.

## 🧹 Data Cleaning Steps

- Dropped unnecessary columns like `description`.
- Converted `date_added` column to datetime format.
- Extracted `year` and `month` from `date_added`.
- Handled null values by dropping or replacing them where appropriate.
- Created a new column for `duration_minutes` for numeric analysis.

## 📈 Visualizations

- Bar plots (for country distribution and content type)
- Count plots (for content type frequency)
- Box plots (to analyze duration of movies)
- Correlation heatmap

## 📁 File Structure

├── netflix.csv
├── netflix EDA.ipynb

## 🚀 How to Run

Clone the repo and run the notebook:

```bash
git clone https://github.com/Kanyira/netflix-eda.git
cd netflix-eda
jupyter notebook
