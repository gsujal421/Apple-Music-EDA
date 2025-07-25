# 🎵 Apple Music App Review Analysis

This beginner-friendly data analysis project explores user reviews from various music apps (including Apple Music) using Python libraries like **Pandas** and **Matplotlib**. The goal is to understand user engagement and satisfaction over time through visual exploration.


---
## 🛠️ Tools & Libraries Used
- `Pandas` – Data manipulation and grouping
- `Matplotlib` – Visualization
- `Datetime` – Handling time series data
---


## 📂 Dataset
The dataset contains user reviews for music applications, with the following key columns:
- **app** – Name of the music application
- **date** – Date of the review
- **rating** – User rating (1–5 stars)
- **review** – Review text (used for counting entries)
- **country** – Country of the reviewer

---

## 🔍 Exploratory Data Analysis (EDA)

The following EDA steps were performed:

- ✅ Checking the **shape** of the dataset (`df.shape`)
- ✅ Using `.head()` and `.info()` to examine structure, column types, and null counts
- ✅ Generating **summary statistics** with `.describe()`
- ✅ **Converting** the `date` column from string to `datetime` format
- ✅ Checking for **null values** and **duplicate rows**
- ✅ Grouping and resampling data by **year** using `resample('Y')` for time-based analysis
- ✅ Aggregating values using `groupby()` to count reviews per app and per country

---

## 📊 Key Analysis & Visualizations

- ⭐ **Rating Distributions**: Pie chart and histogram
- 🧾 **App-wise Analysis**:
  - Average rating per app
  - Number of users (entries) per app
- 📊 **Subplot Comparison**:
  - Side-by-side plot showing **average rating vs. review count** over time

---

