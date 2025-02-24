# RECOMMENDATION-SYSTEM

COMPANY: CODTECH IT SOLUTIONS

NAME: ARYAN SHARMA

INTERN ID: CT08PBS

DOMAIN: MACHINE LEARNING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION: ML Internship Project -RECOMMENDATION SYSTEM

Internship Institution: CODTECH

Task:BUILD A RECOMMENDATION SYSTEM USING COLLABORATIVE FILTERING OR MATRIX FACTORIZATION TECHNIQUES.
This project focuses on clustering movies based on user rating patterns and making genre-independent recommendations using K-Means clustering and Matrix Factorization techniques.

Objective:
Group movies into clusters based on user ratings without using predefined genre labels.
Identify similarities among movies purely through numerical patterns in user feedback.
Provide insights into user preferences and movie trends.
Key Components:
Data Processing & Feature Engineering

The dataset consists of movie ratings by users.
Each movie is represented by user rating patterns rather than metadata like title or genre.
A sparse matrix is created, mapping users and their movie ratings.
Matrix Factorization for Latent Features

A Matrix Factorization model is implemented using PyTorch to extract latent features from the user-movie rating matrix.
This technique helps uncover hidden patterns in user preferences.
K-Means Clustering for Movie Grouping

The K-Means clustering algorithm is applied to group similar movies.
Clusters are formed based on movie rating similarities, revealing genre-like groupings.
Each movie is assigned to a cluster, showing how user responses naturally group them together.
Cluster Analysis & Interpretation

The project prints movie clusters where similar movies appear together.
Example clusters:
Cluster #0 contains classic action and thriller movies like Batman Forever, GoldenEye.
Cluster #3 includes psychological and cult films like Fight Club, Pulp Fiction, and Se7en.
Cluster #7 features fantasy and adventure films like Harry Potter and Titanic.
Results & Insights

Even though the model has no prior knowledge of genres, the clustering naturally groups movies of similar themes.
Movies that have been rated similarly by users tend to belong to the same clusters, proving that numerical patterns can represent genre-like structures.

Technologies Used:
Python (NumPy, Pandas, SciPy, PyTorch)
Machine Learning (Matrix Factorization, K-Means Clustering)
Data Analysis & Visualization (Matplotlib, Seaborn)

OUTPUT:
![Image](https://github.com/user-attachments/assets/0a3c2698-71cc-4045-bf21-5d071b68361f)

![Image](https://github.com/user-attachments/assets/b6335215-af98-4395-86ce-e5c31ab38430)
