# GCD

## Basic Euclidean Algorithm for GCD 
The algorithm is based on the below facts. 

 - If we subtract a smaller number from a larger (we reduce a larger number), GCD doesn’t change. So if we keep subtracting repeatedly the larger of two, we end up with GCD.
 - Now instead of subtraction, if we divide the smaller number, the algorithm stops when we find remainder 0.


## Java 


1. flow -> gcd(n1, n2) = gcd(n2, n1%n2) --->, till n1%n2 =0 ---> gcd(n2,0) ---> result = n2
1. base -> when remainder = 0 return n1  for that call.
1. unintentional-> n1 or n2 < 0 return -1

```java
   //Assume n1> n2
   public static int gcd(int n1, int n2) {
      if (n1 <0 || n2 <0){
       return -1;
      }
      System.out.println(n1 +"," +n2);
      if (n2== 0){
       return n1;
      }
      return gcd(n2, n1%n2);
   }
```
