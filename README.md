# denominator-conjecture-exceptional-type

We verify denominator conejecture for cluster algebras of exceptional types.
Due to the algorithm, it suffices to verify it for type $F_4$ and $E_8$.

First run the file 'E8-B-Matrices.ipynb' to get all the non-acyclic B-matrix of type E_8 up to sink-source equivalent(there are 390 matrices, see'E8Bmatrix.sobj').
Then for each B-matrix $B[i]$, run the file 'E8-D-matrices.ipynb' to obtain all the D-matrices of $B[i]$, see 'D-Matrix-E-8-part1~8'.
Finally, for each file of D-matrices, run the program 'E8-Solving-linear-inequalitiy.ipynb'.
