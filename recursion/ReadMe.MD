# Recursion

 **A way solving a problem by calling the function itself**
 
 1. Any problem using recursion can be solved via iteration

 1. Used in datastuctures like Tree / Graph
 1. Used in algorithum like divide n conquer , greedy ad dynamic programming.

 1. Syntax
    - A method call itself
    - Exit from infinite loop
  
  ```java
  
  public static R m1(Parameters p1){
    if (exit condition satisified){
     return someValue;
    }else {
     m1(modified-p1)
    }
  }
  ```
 
 ## Recursion Vs Iteration 
 
|                  | Recursion    | Iteration | Comments
| -----------------| ------------ |-----------|----------
| Space Efficient  | No           |  Yes      | No stack memory in case of Iteration
| Time Efficient   | No           |  Yes      | In case of recusrion , needs pop n push elements to stack memory
| Easy To Code     | Yes          |  No       | 


## Rules To Follow For Recursion Problem
  - Recursion Case -> defines flow , for ex  n! = n *(n-1)!
  - Base Case  -> the stopping criteria, for ex if n=0 or n=1 we will return 1
  - Unintional Case ->the constraint , for ex if n<0 we return -1



