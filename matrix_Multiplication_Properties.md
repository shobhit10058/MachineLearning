#Properties of Matrix Multiplication

. Matrix Multiplication is not Commutative
. Matrix Multiplication is Associative

* Matlab Code*

```
A = [1, 2; 4, 5]
B = [1, 1; 0, 2]

%Same as writing I = [1, 0; 0, 1]
I = eye(2)

IA = I*A
AI = A*I

AB = A*B
BA = B*A
```
