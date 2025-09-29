
#  Model-Based Collaborative Filtering for Book Recommendations

This repository contains a Jupyter Notebook that builds a **book recommendation system** using **model-based collaborative filtering** with **k-Nearest Neighbors (kNN)**.  

The system recommends similar books based on user ratings, leveraging **cosine similarity** to find nearest neighbors among items.

---

##  Features
- Loads and preprocesses **Books.csv** and **Ratings.csv** datasets.  
- Merges datasets into a unified ratings-book dataframe.  
- Samples data for efficiency in experimentation.  
- Creates a **user–item pivot table** with book titles and ratings.  
- Implements a **kNN model** (`sklearn.neighbors.NearestNeighbors`) for recommendations.  
- Finds and prints the **top-N similar books** to a given title.  

---

##  Dataset
The notebook expects the following files in the working directory:
- **Books.csv** – Metadata of books (ISBN, title, etc.).  
- **Ratings.csv** – User ratings for books.  

