# Decimal to Binary 

## Binary(14) ---> 1110

|        |    Q/2   |   R    |      *10      |      |
| ------ | ---------|--------|---------------|------
|        |    14     |   0   | 0 10 10 10 10 | 0000  
|        |     7     |   1   | 1 10 10 10    | 1000
|        |     3     |   1   | 1 10 10       |  100
|        |     1     |   1   | 1 10          |   10
|        |     0     |   -   |    Result     | 1110 

## Java 


1. flow -> bin(n) = 10 * bin(n/2) +  (n%2) ;
1. base -> n=0 return 0;
1. unintentional-> n<0 return -1

```java
   public static int bin(int n) {
      if (n <0){
       return -1;
      }
     
      if (n ==0){
       return 0;
      }
     
      return  (n%2) + 10 * bin(n/2)  ;
   }
```

