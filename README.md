# 🎬 Latest Movies Dataset Analysis (2025)

## 📌 Project Overview
This project analyzes a dataset of the latest movies releasing around the year 2025. The dataset includes movie details such as title, release date, language, popularity score, ratings, and vote count.  
The goal of this project is to identify patterns, trends, and insights using Python and data visualization techniques in Jupyter Notebook.

---

## 🎯 Research Question
**How do the release month and original language affect movie popularity and ratings, and what is the relationship between popularity and ratings?**

---

## 🛠 Tools & Technologies
| Tool / Library | Purpose |
|----------------|----------|
| Jupyter Notebook | Development & analysis environment |
| Python | Main programming language |
| Pandas | Data loading, cleaning & transformation |
| Matplotlib | Data visualization & charts |

---

## 📁 Dataset Information
- **Filename:** Latest 2025 Movies Datasets.csv
- **Main Columns Used:**  
  `title`, `release_date`, `original_language`, `popularity`, `vote_average`, `vote_count`

---

## 🔧 Steps Performed
1. Imported dataset using Pandas  
2. Cleaned missing values and converted release date to datetime format  
3. Extracted `year` and `month` from release dates  
4. Performed Exploratory Data Analysis (EDA)  
5. Created visualizations:
   - Popularity distribution
   - Ratings distribution
   - Movies by language
   - Popularity by release month
   - Popularity vs rating relationship
6. Answered research question based on findings

---

## 📊 Key Insights (Final Outcome)
- Most movies have average ratings between **5 and 7**
- **Popularity is highest** for movies released in **July, September, and October**
- **English** is the most common language among released movies
- There is a **weak correlation** between popularity and ratings, meaning:
  - High ratings do not guarantee high popularity
  - Popularity is strongly affected by marketing, release timing, and audience hype

### 🎯 Final Conclusion
> Popularity is influenced more by release timing and language than ratings, and not all highly rated movies become popular.

---

## 📂 Project Structure
📁 Movie-Analysis-Project
│── Latest 2025 Movies Datasets.csv
│── analysis_notebook.ipynb
│── README.md
