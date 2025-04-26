# Spotify Song Popularity and Recommendation Project

This project analyzes how various audio features of songs relate to their popularity and builds models to perform popularity prediction, genre classification, and song recommendation.

## 📁 Project Files

| File | Description |
|------|-------------|
| `preprocessing_eda.ipynb` | Initial data cleaning, feature selection, and EDA |
| `prediction_model.ipynb` | Main notebook for regression, genre classification, and neural network modeling |
| `rating_analysis.ipynb` | Analysis and modeling based on user ratings from `starRating.csv` |
| `spotify52kData.csv` | Main dataset with ~52,000 Spotify songs and audio features |
| `spotify_songs.csv` | Raw or supplementary Spotify dataset |
| `1007_project_slide_Team_One.pptx` | Final presentation slide deck |
| `README.md` | Project overview and instructions |

> 🔺 **Note**: `starRating.csv` is not included here due to file size limitations on GitHub. If needed, please contact the authors to obtain it or use your own rating dataset with the same format.

---

## 🔍 Key Research Questions

1. Is there a relationship between song length and popularity?
2. Are explicit songs more popular?
3. Does musical key (major/minor) affect popularity?
4. Which audio features best predict popularity?
5. Can we build a better multivariate model for popularity?
6. Can PCA and clustering reveal genre groupings?
7. Can we predict genre using neural networks?
8. Can we build personalized recommender systems?

---

## 🧠 Models and Methods

- **Regression**: Linear & Ridge Regression on popularity
- **Classification**: Logistic Regression, SVM, Decision Tree, XGBoost
- **Dimensionality Reduction**: PCA + Clustering
- **Recommender Systems**:
  - Popularity-based
  - Latent Factor (SVD)
  - Content-based filtering

---

## 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/spotify-popularity-recommender.git
   cd spotify-popularity-recommender
