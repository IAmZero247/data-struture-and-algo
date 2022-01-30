# Factorial


## Java 


1. flow -> n! = n * (n-1)!
1. base -> 1! =1 or 0! =1
1. unintentional-> n<0 return -1

```java
  public static int fact(int n) {
      if (n <0){
       return -1;
      }
     
      if (n ==1 || n ==0){
       return 1;
      }
     
      return n * fact(n-1);
   }
```
