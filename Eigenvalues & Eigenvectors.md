---

Eigenvalues and eigenvectors are fundamental concepts in linear algebra used in various applications, including stability analysis and dimensionality reduction. NumPy provides functions to compute these:

* **`np.linalg.eig()`**: This function returns both the eigenvalues and eigenvectors of a square matrix. The eigenvalues represent the scaling factors, while the eigenvectors indicate the directions along which these scaling occur.

Compute the eigenvalues and eigenvectors of a matrix:

````python
eigen_vals, eigen_vecs = np.linalg.eig(b)
````
