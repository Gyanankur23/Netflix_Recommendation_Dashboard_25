# Netflix_Recommendation_Dashboard_25 CaseCraft Analytics Project Sprint Project 25

## 🎬 Overview  
This project builds a modular Netflix recommendation dashboard using synthetic user ratings, genre metadata, and collaborative filtering. It blends matrix construction, genre affinity, and visual storytelling to optimize viewer engagement and personalization.

## 🎯 Objective  
To simulate user-movie interactions, apply cosine similarity for recommendations, and visualize genre trends, device usage, and content affinity.

## 🧾 Dataset & Features  
- **Movies**: 20 titles with genre, release year, duration  
- **Users**: 10 profiles with subscription type and region  
- **Ratings**: 50 user-movie ratings (1–5 stars)  
- **Watch History**: 100 viewing sessions with device and timestamp  
- **Features**:  
  - `genre`, `rating`, `device`, `timestamp`, `subscription_type`, `region`

## 📊 Visual Explorations  
- **Strip Plot**: Genre popularity  
- **Boxplot**: Ratings by genre  
- **Word Cloud**: Genre frequency  
- **Heatmap**: Device engagement by top users  
- **Heatmap**: Content similarity matrix (cosine scores)  
- **Sankey Diagram**: User-to-genre recommendation flow

## 🧠 Recommendation Logic  
- **Matrix Construction**:  
  - User-item ratings matrix  
  - Item-item similarity matrix via TF-IDF and cosine similarity  
- **Filtering**: Genre-based and subscription-aware  
- **Modularity**: Markdown/code separation for reproducibility

## 🧠 Key Insights  
1. **Genre Saturation**: Drama, Action, and Comedy dominate the catalog  
2. **User Preference**: Sci-Fi and Crime genres receive higher ratings  
3. **Device Usage**: Mobile and TV are top platforms for engagement  
4. **Similarity Matrix**: Enables scalable, content-based recommendations  
5. **Sankey Flow**: Visualizes genre affinity without network clutter  
6. **Modular Design**: Supports future deployment and dataset expansion

## ✅ Final Conclusion  
The Netflix dashboard delivers clarity-first personalization using genre filters, cosine similarity, and modular visuals. It balances strategic insight with clean formatting—ideal for content targeting, viewer retention, and platform extension. Ready for real-world deployment or adaptation to other streaming services.