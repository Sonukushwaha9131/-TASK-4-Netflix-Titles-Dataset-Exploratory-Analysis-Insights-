Based on the analysis of the provided notebook, here is a professional README for your GitHub repository:

---

# Netflix Titles Data Analysis

This project performs exploratory data analysis (EDA) and feature engineering on the [Netflix Titles dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows). The analysis focuses on understanding content distribution, identifying popular genres, and exploring production trends across different countries and time periods.

## 🚀 Overview

The project uses Python and popular data science libraries to clean the raw dataset and extract actionable insights through visualization. Key tasks include:
* **Data Cleaning:** Handling missing values in `director`, `cast`, and `country` fields.
* **Feature Engineering:** Extracting primary genres, primary production countries, and categorizing content by release decades.
* **Visual Insights:** Analyzing the ratio of Movies vs. TV Shows and identifying global content trends.

## 🛠️ Tech Stack

* **Language:** Python 3
* **Libraries:** * `pandas`: Data manipulation and cleaning
    * `matplotlib`: Core visualization
    * `seaborn`: Advanced statistical plotting

## 📊 Key Findings & Visualizations

The notebook generates a multi-panel dashboard providing the following insights:
1.  **Content Distribution:** A pie chart showing the percentage breakdown between Movies and TV Shows.
2.  **Release Trends:** A line plot tracking the volume of content released per year since 2000.
3.  **Genre Popularity:** A bar plot identifying the top 10 most frequent genres on the platform.
4.  **Geographic Distribution:** A heatmap visualizing the concentration of content across the top 5 producing countries.

## 📂 Project Structure

* `Task_4_Netflix_Titles_Dataset.ipynb`: The main Jupyter notebook containing the analysis code and visualizations.
* `netflix_titles.csv.zip`: The source dataset containing metadata for movies and TV shows available on Netflix.

## ⚙️ How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/netflix-analysis.git
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas matplotlib seaborn
    ```
3.  **Run the notebook:**
    Ensure you have the `netflix_titles.csv.zip` file in the same directory as the notebook and run all cells in `Task_4_Netflix_Titles_Dataset.ipynb`.

## 📈 Feature Engineering Details

To improve the analysis, several new features were derived:
* `release_decade`: Grouped years into decades to see long-term production trends.
* `primary_country`: Extracted the first country listed for multi-national productions.
* `primary_genre`: Extracted the lead genre from the `listed_in` column.
* `is_movie`: A binary indicator for categorical filtering.

---
