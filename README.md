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
