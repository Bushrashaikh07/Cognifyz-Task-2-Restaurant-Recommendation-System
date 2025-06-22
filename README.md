#  Restaurant Recommendation System

### Task 2 – Machine Learning Internship @ Cognifyz Technologies

This project is a **content-based restaurant recommendation system** developed as part of Task 2 during my internship at **Cognifyz Technologies**.

---

## Objective

To build a system that recommends restaurants based on user preferences such as cuisine type and price range using **TF-IDF** and **cosine similarity**.

---

##  Key Features

- ✅ Cleaned and preprocessed restaurant data
- ✅ Combined cuisine and city info into a new 'Tags' feature
- ✅ Used **TF-IDF Vectorization** to convert text into feature vectors
- ✅ Calculated **cosine similarity** to find similar restaurants
- ✅ Built a dynamic recommendation function
- ✅ Visualized recommendations with **Seaborn bar plots**

---

## 📂 Dataset

- Source: Given by cognifyz team
- Columns used:
  - `Restaurant Name`
  - `Cuisines`
  - `City`
  - `Price range`
  - `Aggregate rating`

---

## Tools & Libraries

- `Python`
- `Pandas`
- `Scikit-learn`
- `Matplotlib & Seaborn`
- `Jupyter Notebook`

---

##  How It Works

1. User provides a **cuisine keyword** and a **price range** (1–4).
2. The system filters relevant restaurants.
3. It sorts them by **aggregate rating**.
4. Results are displayed in a table and as a bar chart.

---

##  Sample Output

```bash
Sample Recommendation for: North Indian | Price Range: 2

| Restaurant Name  | Cuisines         | City     | Price range | Aggregate rating |
|------------------|------------------|----------|--------------|------------------|
| Taj Foods        | North Indian     | Delhi    | 2            | 4.5              |
| Punjab Grill     | North Indian     | Delhi    | 2            | 4.3              |

## Plot
Visual representation of recommended restaurants based on their ratings.


## Acknowledgement
Thanks to Cognifyz Technologies for providing this internship opportunity.

## Links
📌 LinkedIn Post

📁 Notebook File

## Author
Bushra Shaikh
** Machine Learning Intern **
** June 2025 – Cognifyz Technologies**
## MLJourneyWithBushra


