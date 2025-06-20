# Netflix Exploratory Data Analysis

This project performs an exploratory data analysis (EDA) on a Netflix dataset using Python in a Jupyter Notebook. The goal is to explore and visualize key insights such as content trends, popular ratings, genre distributions, and more.

---

## Dataset
The dataset used is the [Netflix Movies and TV Shows](https://www.kaggle.com/code/experience08/netflix-eda/input) dataset from Kaggle. It contains information about TV Shows and Movies available on Netflix.

**Main columns include:**
- title
- type (Movie or TV Show)
- director
- cast
- country
- date_added
- release_year
- rating (e.g. TV-MA, TV-14)
- duration
- listed_in (genres)
- description

---

## Technologies Used

- Python 
- Jupyter Notebook 
- pandas
- numpy
- seaborn

---

## Key Objectives

- Clean and preprocess the dataset
- Analyze the distribution of content types (Movies vs TV Shows)
- Identify top genres and countries producing content
- Analyze content added over time
- Visualize the most common ratings (TV-MA, TV-14, etc.)

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Netflix-Exploratory-Data-Analysis.git
cd Netflix-Exploratory-Data-Analysis
```
---

2. Install dependencies

   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```
---
3. Launch Jupyter Notebook
   ```bash
   jupyter notebook
   ```
---
## Insights
- The majority of the content is Movies.
- Top 10 watched Genres are International Movies, Dramas, Comedies, Action and Adventure, Independent Movies, Romantic Movies, Thrillers, Childern and Family Movies, Documentaries and Horror Movies.
- United States, India, and UK produce the most Netflix content.
- Most content on Netflix is rated TV-MA, TV-14 and R.
- 2017 is the year most movies were added.
  
---

## Acknowledgements
- [Netflix Dataset on Kaggle](https://www.kaggle.com/code/experience08/netflix-eda/input)
- Python and data visualization libraries community


