# Fibonacci
**1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, …**

## Java 




1. flow -> fib(n) = fib(n-1) + fib(n-2)
1. base -> fib(1) =1 or fib(0) =0
1. unintentional-> n<0 return -1

```java
  public static int fib(int n) {
      if (n <0){
       return -1;
      }
     
      if (n ==1 || n ==0){
       return n;
      }
     
      return fib(n-1) + fib(n-2);
   }
```

