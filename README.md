# LinearAlgebra For Computer Science

- Eigenvalues and eigenspaces
- Image and kernel
- Determinants
- Dual space
- Transpose
- Inner products
- Singular value decomposition

## Eigenvalues and eigenspaces

```
For eigenvalues and eigenvectors, Google's original PageRank algorithm is a good example. The idea is to build a matrix A where Aij is the probability that you would end up at page i by following a randomly chosen hyperlink on page j. An eigenvector with eigenvalue 1 of this matrix is a stable probability distribution over web pages. Generally a page which is linked to by many sites which are themselves linked to by many sites will have a high page rank.

Singular value decomposition is widely used for image processing. You can represent a black-and-white image by the matrix of values for its pixels. The k largest singular values represent the most significant contributions to the image. You can then compress an image by replacing A=UDVT with U′D′(V′)T, where D′ is the k×k matrix submatrix of D of the largest singular values, U′ is the n×k submatrix of U consisting of the corresponding k columns of U, and (V′)T is the submatrix of VT consisting of the corresponding k rows of VT.

Computer graphics is another area where linear algebra plays a huge role. Consider the problem of finding the shadow of triangle onto some plane from a light source infinitely far away. This is just a projection map.
```

Credits: https://mathoverflow.net/questions/322691/applications-of-basic-linear-algebra-concepts-to-computer-science

