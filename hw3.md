# CS 559 WS: Machine Learning: Fundamentals and Applications
Due: 10/9/2023 Monday 11:59 p.m.
The assignment must be individual work and must not be copied or shared. Any tendency to cheat/copy evidence will lead to a 0 mark for the assignment. Students must only use Pandas, NumPy, and Spacy if the coding problem does not specify libraries/packages. Use of other libraries than specified will be penalized. All problems must be submitted in a single notebook file except the question 1.a. All files must be compressed into a single zip file as Name HW#.zip.



1 LDA with Least Square [40 pts]
Suppose the data set has X = [x1,x2,...,xN] and yi ∈ {C1,C2}. This problem task is to show that the Fisher criterion J(w) can be considered as a special case of least squares.
2
a.
[20 pts, paper] The sum squared error function is E = 1 PN (wTx +w −y )2. Show that 2 i=1 i 0 i
the gradient of E can be analytically expressed as following
S +N1N2Sw=N(m−m). (1)
hint: the total sum of target is
XN N N
yi =N1N −N2N =0
set with four features and two classes.
from sklearn import datasets
X, y = datasets.make blobs(n samples = 200, n features= 4,
centers = 2, cluster std= 2, random state= 100)
[3 pts] Using Scikit-learn LDA, fit the train data and determine the weight vector w.
[15 pts] Note that SB w in Equation (1) is always in the direction of (m2 − m1 ). Compute the w vector from Equation 1. Compare the direction of w vectors from 1.c. For this problem, use NumPy only.

...
