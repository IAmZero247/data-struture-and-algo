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
  - Unintentional Case ->the constraint , for ex if n<0 we return -1

## Example . powerOf2 


   ```
   2^2 = 2* 2
   2^3 = 2*2*2
   2^n = 2*2*2...*2
   
   recursion case -> 2^n = 2 * 2^(n-1)
   base case -> 2^1 = 2 and 2^0 =1
   unintentional case => n<-1 return -1 
   ```
   
1. Recursion
   
   ```java
   public static int powerOf2(int n){
      
      if(n<0){
      return -1;
      }
      if(n ==0){
      return 1;
      }else{
      int r = 2*powerOf2(n-1);
      return r;
      }
   }
   ```

2. Iteration   
   
   ```java
   
   public static int powerOf2(int n){
     int b=0
     int r =1;
     while(b<=n){
     r = r *2
     b = b+1;
     }
     return r;
   }
   
   //n =4
   //b1-b2 r  n
   //0-1   2  4
   //1-2   4  4
   //2-3   8  4
   //3-4   16 4 
   //4 while breaks
   ```


