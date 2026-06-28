# 🎬 Netflix Movie Dataset — Exploratory Data Analysis

An exploratory data analysis (EDA) project on a movie metadata dataset, uncovering patterns in genre distribution, audience reception, and release trends across more than a century of films.

---

## 📌 What This Project Covers

- Data cleaning and preprocessing (date formatting, dropping unused columns, handling multi-valued genre fields)
- Categorizing films by audience reception (`popular`, `average`, `below-average`, `not-popular`) based on vote averages
- Splitting and exploding multi-genre entries to analyze genre-level frequency accurately
- Visualizing:
  - Genre distribution across the dataset
  - Vote-average category distribution
  - Release-year trends from 1902 to 2024
- Identifying the most and least popular titles by popularity score

---

## 🛠 Tech Stack

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy** — data cleaning & transformation
- **Matplotlib, Seaborn** — visualization

---

## 📂 Dataset

A movie metadata dataset containing release date, title, popularity score, vote count, vote average, original language, and genre for each entry.

**Size:** 9,837 records · **Unique genres:** 19 (after splitting multi-genre fields) · **Release range:** 1902–2024

---

## 📊 Verified Findings

- **Top genres by frequency:** Drama, Comedy, and Action lead the dataset, with Drama appearing most often across titles
- **Vote-average categorization:** Films were bucketed into four reception tiers (not-popular → popular) using quartile-based cuts on the vote average column, giving a clearer picture of how reception is distributed across the catalog
- **Release trend:** The dataset spans over a century of releases (1902–2024), with a release-year histogram used to visualize how volume has shifted over time

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Shubham1919284/Netflix_Content_Analysis.git
cd Netflix_Content_Analysis
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Run the notebook

```bash
jupyter notebook Netflix_Analysis.ipynb
```

---

## 🔮 Future Enhancements

- Add a true Netflix-catalog dataset (with content type, country, and maturity rating fields) for platform-specific insights
- Add genre-vs-popularity correlation analysis
- Build an interactive dashboard (Streamlit or Power BI) on top of the existing findings

---

## 🙌 Let's Connect

If you find this project interesting, feel free to ⭐ the repo and share your thoughts!

- 🔗 [LinkedIn – Shubham Kumar Jha](https://www.linkedin.com/in/shubham-kumar-jha-1a2b3c)
- 💻 [GitHub – Shubham1919284](https://github.com/Shubham1919284)
