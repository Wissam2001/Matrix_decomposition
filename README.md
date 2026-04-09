# Matrix Decomposition for Machine Learning: A Mathematical Lab Project 📐
This project was developed as a Master's Lab project in Mathematics for Machine Learning, focusing on two fundamental matrix decomposition techniques:
- **LU Decomposition:** Breaking a square matrix into Lower and Upper triangular matrices
- **Singular Value Decomposition (SVD):** A more general decomposition for any matrix, widely used in dimensionality reduction, recommendation systems, and data compression

The project demonstrates how these mathematical techniques form the backbone of many machine learning algorithms, implemented from scratch and validated against established libraries.

# Project Objectives 🎯
- **Implement LU Decomposition from scratch:** Understand Gaussian elimination as matrix factorization
- **Implement SVD from scratch:** Derive singular values and singular vectors through eigen-decomposition of AᵀA
- **Verify implementations:** Compare with scipy.linalg.lu and scipy.linalg.svd
- **Understand mathematical foundations:** Connect linear algebra theory to practical computation
- **Apply to real problems:** Show how decompositions enable solving linear systems and dimensionality reduction

# Lessons Learned 💡
 ## LU Decomposition Insights
 - **Applicable for square matrices only**
 - **Memory efficiency:** L and U can overwrite A (in-place computation)
 -  **Pivoting is essential:** Without row swaps, zero pivots break the algorithm
 -  **Computational cost:** O(n³) for decomposition, but only O(n²) to solve each subsequent system
 -  **Applications:** Solving linear systems, computing determinants, matrix inversion

## SVD Insights
- **Most general decomposition:** Works for any matrix (square, rectangular, singular)
- **Rank revelation:** Number of non-zero singular values = matrix rank
- **Energy compaction:** First singular value captures most of the matrix "energy"

## Applications in ML:
- Principal Component Analysis (PCA)
- Recommendation systems (collaborative filtering)
- Image compression
- Latent semantic analysis (NLP)

 # License 📝
  This project is for educational purposes as part of a Master's lab assignment.

# Contact ✉️
- **Email:** wissambadia4@gmail.com
- **LinkedIn:** [Badia Ouissam Lakas](linkedin.com/in/badia-ouissam-lakas-a66a28214)  

