###### Properties of Matrix Multiplication

* Matrix Multiplication is not Commutative
* Matrix Multiplication is Associative

*Matlab Code*

``` Matlab
A = [1, 2; 4, 5]
B = [1, 1; 0, 2]

%Same as writing I = [1, 0; 0, 1]
I = eye(2)

IA = I*A
AI = A*I

AB = A*B
BA = B*A
```


###### Inverse and Transpose

* Inverse
A * InverseOfA = I

* Transpose

TransposeOfA = A'

*Matlab Code*

``` Matlab

A = [1, 2, 0; 0, 5, 6; 7, 0, 9]

A_Trans = A'

A_inv = inv(A)
% If using octave the write pinv() instead of inv()

A_invA = inv(A)*A

```
