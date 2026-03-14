# 🎬 Movie Recommendation System
Built as a beginner Machine Learning project to understand recommendation systems.

This project implements a **Movie Recommendation System** using Python and the **MovieLens dataset**.  
The system recommends movies similar to a given movie based on user rating patterns.

It uses **collaborative filtering** by calculating correlation between movies from a **user–movie rating matrix**.

## 📂 Dataset

The dataset used is the **MovieLens Latest Small dataset**.
Files used:
- ratings.csv
- movies.csv

## 🛠 Technologies Used
- Python
- Pandas
- Jupyter Notebook
- MovieLens Dataset

## ⚙ Project Workflow
1. Load the ratings and movies datasets  
2. Clean movie titles  
3. Merge datasets using `movieId`  
4. Create a **user–movie rating matrix**  
5. Compute correlations between movies  
6. Recommend **top similar movies**

## 🎥 Example

**Input**
Toy Story
**Output**
Recommended Movies:
Toy Story 2
Aladdin
Lion King
Finding Nemo

## 📁 Project Structure

movie_recommendation_system
│
├── MOVIE_RECOMMENDATION.ipynb
├── movies.csv
├── ratings.csv
└── README.md


## 👩‍💻 Author

**B. Saran Pyari**
