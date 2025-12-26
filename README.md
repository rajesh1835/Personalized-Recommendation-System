# Personalized-Recommendation-System
A hybrid recommendation system implemented using collaborative filtering and content-based filtering techniques with implicit user feedback and synthetic interaction data.

# Hybrid Recommendation System

This project implements a **Hybrid Recommendation System** using **Collaborative Filtering** and **Content-Based Filtering** techniques.  
The system is designed to work with **implicit user feedback**, where user behavior such as browsing and purchasing is converted into interaction data.

⚠️ This project focuses **only on the recommendation engine** and does **not** implement a full e-commerce platform.

---

## 📌 Project Scope

### ✅ Implemented
- Data exploration and preprocessing
- Synthetic interaction data generation
- Train–test split (time-based)
- Collaborative Filtering (User-Based)
- Content-Based Recommendation (Category-Based)
- Hybrid Recommendation (CF + Content-Based)
- OS-independent path handling

### ❌ Not Implemented
- Full e-commerce platform features
- User authentication
- Payments or order management
- Sentiment-based or deep learning recommendations

---

## 🧠 Recommendation Techniques Used

### 1. Collaborative Filtering
- User-based collaborative filtering
- Uses cosine similarity
- Recommends products liked by similar users

### 2. Content-Based Filtering
- Category-based recommendation
- Builds user preference profile from interaction history
- Recommends items from preferred categories

### 3. Hybrid Recommendation
- Combines collaborative and content-based scores
- Weighted aggregation:
  - Collaborative Filtering: 60%
  - Content-Based Filtering: 40%

---

## 📂 Dataset Description

The original dataset contains:
- Customer browsing history
- Customer purchase history
- Contextual information (season, holiday)

Since explicit product interactions were not available, **synthetic interaction data** was generated.

### Final Interaction Dataset Columns


### Rating Scheme (Implicit Feedback)
| User Behavior | Rating |
|--------------|--------|
Browsing | 2 |
Purchase | 5 |

---

## 📊 Data Split

- **80% Training Data**
- **20% Testing Data**
- Split is performed **chronologically** using timestamps to avoid data leakage.

---

## 🗂️ Project Structure


---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
2️⃣ Run the Recommendation Model

Run from the project root directory:

python -m src.components.model


⚠️ Do not run the file directly using its path.

🧪 Output

The system prints:

Collaborative Filtering recommendations

Content-Based recommendations

Final Hybrid recommendations for a given user

🧩 Key Features

Uses implicit feedback

Modular and readable code structure

Fully OS-independent path handling

Easy to extend for evaluation or UI integration

🎓 Academic Relevance

This project demonstrates:

Practical recommender system design

Handling real-world data limitations

Hybrid recommendation logic

Clean and professional Python project structure

📚 References

Schafer, J. B., Konstan, J. A., & Riedl, J. (2001).
E-commerce recommendation applications.

Adomavicius, G., & Tuzhilin, A. (2005).
Toward the next generation of recommender systems.

Ricci, F., Rokach, L., & Shapira, B. (2011).
Recommender Systems Handbook.
