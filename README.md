# CSE548-AMS542-Homework-3-solution

Download Here: [CSE548/AMS542 Homework 3 solution](https://jarviscodinghub.com/assignment/cse548-ams542-homework-3-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. Textbook [Kleinberg & Tardos] Chapter 5, page 246, problem #3, #5, #6.
2. Solving recurrences. Find the asymptotic order of the following recurrence, represented in
big-Θ notation. (Each subproblem is 5 pts; the last problem is an extra credit problem.)
(a) A(n) = 4A(bn/2c + 5) + n
2
(b) B(n) = B(n − 4) + 1/n + 5/(n
2 + 6) + 7n
2/(3n
3 + 8)
(c) C(n) = n + 2√
nC(
√
n) Hint: take H(n) = C(n) + n.
3. Square of a matrix. The square of a matrix A is its product with itself, AA.
(a) Show that 5 multiplications are sufficient to compute the square of a 2 × 2 matrix. (5pts)
(b) What is wrong with the following algorithm for computing the square of an n×n matrix?
(5pts)
Use a divide-and-conquer approach as in Strassen’s algorithm, except that instead
of getting 7 subproblems of size n = 2, we now get 5 subproblems of size n = 2
thanks to part (a). Using the same analysis as in Strassen’s algorithm, we can
conclude that the algorithm runs in time O(n
log2 5
).
(c) In fact, squaring matrices is no easier than matrix multiplication. In this part, you will
show that if n × n matrices can be squared in time S(n) = O(n
c
), c ≥ 2, then any two
n × n matrices can be multiplied in time O(n
c
). (5pts)
i. Given two n×n matrices A and B, show that the matrix AB +BA can be computed
in time 3S(n) + O(n
2
).
ii. Given two n × n matrices X and Y , define the 2n × 2n matrices A and B as follows:
A =

X 0
0 0 
; B =

0 Y
0 0 
What is AB + BA, in terms of X and Y ?
iii. Using (i) and (ii), argue that the product XY can be computed in time 3S(2n)+O(n
2
).
Conclude that matrix multiplication takes time O(n
c
).
