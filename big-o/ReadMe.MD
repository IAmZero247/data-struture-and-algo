# Big O 

  **A metric we used to describe the efficiency of algorithms**
  
  **Time Complexity -> a way of showing how runtime increases as size of input increases**
  
  **Space Complexity -> a way of showing how the memory consumation increase as size of input increases**

  Refer -> https://www.bigocheatsheet.com/
  
 
## Big O , Big Omega , Big Theta
  
 1. Big O : complexity less or equal to worst case.
 1. Big Omega : complexity that atleast more then the best case 
 1. Big Theta : complexity within the bound between best and worst case
    
 1. Below example with an array of n element. 

     [![Image](https://github.com/IAmZero247/data-strutures-and-algorithms/blob/main/imgs/big-o/bigO_bigOmega_bigTheta.jpg)]
  
    
    
## Complexity Chart    
     
     [![Image](https://github.com/IAmZero247/data-strutures-and-algorithms/blob/main/imgs/big-o/bigO_complexity_chart.jpg )]
      
     
## Examples - Time Complexity 
  
| Complexity | Recursion    | Examples
| -----------| ------------ |-----------------------------------------
| O(1)       | Contstant    |  Accesing a specific element in array
| O(N)       | Linear       | Iterating whole element from a array
| O(LOGN)    | Logarithmic  | Find an element in sorted array
| O(N^2)     | Quadratic    | Looking at every index in a array twice
| O(2^N)     | Exponential  | Double recursion in fibonacci

## Examples - Space Complexity 

  
  1. Example 1
  ![Image](https://github.com/IAmZero247/data-strutures-and-algorithms/blob/main/imgs/big-o/sp_complexity1.jpg)
  
  2. Example 2 - The call inside iteration are not dependent on value from previous iteration
  ![Image](https://github.com/IAmZero247/data-strutures-and-algorithms/blob/main/imgs/big-o/sp_complexity2.jpg)
      
  
  
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
- - [ ] Mercury
+ - [x] Venus
@@ text in purple (and bold)@@
```

 - [ ] Mercury
  - [x] Venus
