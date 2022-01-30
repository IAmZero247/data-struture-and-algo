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
 
 
 
|                  | Recursion    | Iteration | Comments
| -----------------| ------------ |-----------|----------
| Space Efficient  | No           |  Yes      |
| Time Efficient   | No           |  Yes      |
| Easy To Code     | Yes          |  No       |
