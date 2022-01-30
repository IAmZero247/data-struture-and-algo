# Recursive Range

1. fun accepts a number and add all the number from 0 to the number passedd to the function


## Java

 ```java


   recursiveRange(10) -> 55
   recursiveRange(7) -> 28 

   public int recursiveRange(int num) {
       if(num<0)
       return -1;
       if(num ==0)
       return 0;
       return recursiveRange( num-1) + num;
   } 

 ```
