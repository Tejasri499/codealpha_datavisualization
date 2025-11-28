# Quotes EDA Project

## Project Overview
This project demonstrates **Exploratory Data Analysis (EDA)** on a small dataset of famous quotes. The dataset includes quotes, authors, and tags. Through this analysis, we explore:

- Most prolific authors
- Most common tags
- Quote length distribution
- Relationships between authors and tags

---

## Dataset
The dataset is embedded directly in the code. It contains the following columns:

| Column | Description |
|--------|-------------|
| **Quote** | Text of the quote |
| **Author** | Name of the author |
| **Tags** | Comma-separated tags describing the quote |

**Sample Data:**

| Quote | Author | Tags |
|-------|--------|------|
| "The world as we have created it is a process of our thinking. It cannot be changed without changing our thinking." | Albert Einstein | change, deep-thoughts, thinking, world |
| "It is our choices, Harry, that show what we truly are, far more than our abilities." | J.K. Rowling | abilities, choices |

---

## Steps Performed

### 1. Data Cleaning
- Removed extra spaces in author names
- Filled missing tags with `"unknown"`
- Converted `Tags` column to a list for per-tag analysis
- Used `explode` to expand multiple tags

### 2. Visualizations
1. **Bar Chart:** Top Authors by Number of Quotes
2. **Pie Chart:** Distribution of quotes by author
3. **Bar Chart:** Top 10 most common tags
4. **Heatmap:** Author-Tag relationship
5. **Histogram:** Distribution of quote lengths (word count)

---

## Libraries Used
- `pandas` – Data manipulation and cleaning
- `matplotlib` – Plotting library
- `seaborn` – Statistical visualizations
- `io` – Reading CSV data from string

---

## How to Run
1. Copy the code into a Python environment (Jupyter Notebook, Google Colab, etc.)
2. Run all cells sequentially
3. View cleaned data and visualizations

---

## Future Enhancements
- Expand dataset with more quotes
- Perform sentiment analysis on quotes
- Generate word clouds for tags and quotes
- Create an interactive dashboard using Streamlit or Plotly

---

