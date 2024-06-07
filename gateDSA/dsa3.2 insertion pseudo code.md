## pseudo code

u can use variables, if-else, for-while, functions in  pseudo code as they are general things in any programming language 

>> Introduction to Algorithms{Book} best pseudocodes
1. for j=2 to A.length
2.  key = A[j]
3.  //  insert A[j] into the sorted A[1...j-1]
4.  i=j-1
5.  while i>0 AND A[i] > key
6.      A[i+1] = A[i]
7.      i--
8. A[i+1] = key