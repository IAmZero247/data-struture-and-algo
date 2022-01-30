# Prod Of Array

1. int arr[] = [1,2,3,4,5]
2. productofArray(arr, arr.length)  -> 120

## Java 

  ```java
    public int productofArray(int A[], int N) 
    { 
     if (N ==0) 
         return 1;
     return  A[N-1] * productofArray (A, N-1) ;         
    } 
  ```
