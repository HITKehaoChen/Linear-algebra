# Linear-algebra
Linear Algebra Learning
When I was a freshman，I didn't concentrate on maths.So when I need using Linear Algebra, I realised that I need to learn Linear Algebra again.

Basicly I take some courses in youtube,and do some practice. 

2018/7/5  Matrix Elimination

 MITStrangLec02

- A->U is an important calculation.It is so important that people try finding better way to calculate this one.
- U is upper triangular matrix.
- Pivot cannot be 0.
- multiply the pivots..... equals the result of determinant.
- The basic method can failure for a moment.
- 
- How could this fail? (Fail to come up with three pivots)
  - If 0 takes the positon for pivots, you need to exchange rows,to get a proper pivot.(Temporary Failure)
  - if the last pivot is 0,you cannot exchange rows... this is a big trouble.(Completely Failure)
  - So,there is no 3rd pivot. and the matrix is not invertible.
- Back to Success.
- Back substitution
  - bring the right hand side in
  - Bring the right hand in ,then we call it augmented matrix(增广矩阵)
    - you tacked on this extra column. b is the new column.
    - remember the vector c
    - C is what happens to b
    - U is what happens to A
  - Ux = c 
- Matrix operations.
- Elimination matrices.
- important!! work by rows & cols.
- combining the rows. linear combination of rows.
- the identity matrix
- . \begin{matrix} 1 & 0 & 0 \\ 0 & 1 &0 \\ 0 & 0 & 1 \end{matrix} \tag{identity matrix}  
- (E_1)(E_2A) = （E_1E_2)A =U  associative law. 结合律。
- Permutation Matrix. 
- \begin{matrix} 0 & 1\\ 1 & 0\\\end{matrix}\tag{Permutation}
-  \begin{matrix} 0 & 1\\ 1 & 0\\\end{matrix}\tag{Permutation} 
- \begin{matrix} a & b\\ c & d\\\end{matrix} -->\begin{matrix}  c& d\\ a & b\\\end{matrix}
- multiply in the left --> row operations;
- multiply in the right --> col operations;
- inverse is import U BACK TO A 
