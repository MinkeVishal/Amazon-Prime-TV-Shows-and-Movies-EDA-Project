# 🎬 Amazon Prime Video – TV Shows & Movies EDA

An exploratory data analysis (EDA) project focused on analyzing **TV Shows and Movies** available on **Amazon Prime Video**. This project aims to understand content performance, user ratings, runtime patterns, and age distribution to uncover insights that can drive business and content strategy.

---

## 📊 Project Objective

The main objectives of this project are to:

- Analyze **IMDb and TMDB scores** across content types.
- Understand how **content type, runtime, and age certification** affect viewer ratings.
- Identify trends in **content release years** and audience preferences.
- Provide actionable insights to help the platform improve **content curation and engagement**.

---

## 🧰 Tools & Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **Plotly**
- **Scikit-learn (optional)** for feature correlation or clustering
- **Amazon Prime Video Dataset**

---

## 📂 Dataset

**Source:** [Provide dataset link if public]

The dataset includes the following fields:
- `title`
- `type` (Movie or TV Show)
- `release_year`
- `age_certification`
- `runtime`
- `genres`
- `imdb_score`
- `tmdb_score`
- `popularity`

---

## 📌 Key Features & Insights

- Cleaned and preprocessed the dataset (handled nulls, type conversions).
- Explored the distribution of **Movies vs. TV Shows**.
- Visualized **runtime vs. rating**, and **year-wise IMDb trends**.
- Created heatmaps and pair plots to examine correlations.
- Analyzed **age certifications** by content type.
- Identified gaps in **content targeting by age group**.

---

## 📈 Visualizations

Key visualizations included:
- Content type distribution (Movies vs TV Shows)
- IMDb score trends over release years
- Runtime vs. IMDb score scatter plot
- Age certification count plots by type
- Average ratings by content type
- Correlation heatmap for scores, popularity, and runtime
- Pair plot showing feature clusters for Movies and Shows

---

## 💡 Conclusion

- **IMDb and TMDB scores are highly correlated**, validating cross-platform consistency.
- **No strong correlation between runtime and user ratings**, implying content length doesn't determine quality.
- **TV-MA and R-rated content dominates**, highlighting an opportunity to expand into **family and youth segments**.
- Popularity doesn't always align with ratings, suggesting potential to **promote high-rated hidden gems**.

---

## 🚀 Future Work

- Perform clustering to group content based on combined metrics.
- Create recommendation logic using rating and popularity data.
- Extend analysis with **regional data** (if available) for localization strategy.
- Build a dashboard to allow interactive filtering of content trends.

---

## 📁 How to Run

1. Clone the repository:
```bash
git clone https://github.com/MinkeVishal/amazon-prime-eda.git
