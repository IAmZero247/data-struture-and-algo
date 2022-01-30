
# Sum Of Digits 

- n = 15 -> 1+5 = 6
- n = 99 -> 9+9 = 18

- n= 789 -> 7+8+9=24 

```
  Logic is divide by 10 , get remainder 
  Divide quotient by 10  until the quotient is 0 , get remainder and do summation 


   For Eg 
   789 -> q=78 r=9
          q=7  r=8
          q=0  r=7
          ........
                 9+8+7=24
```
## Java 


1. flow -> sumOfDigits(n) = sumOfDigit(n/10) + n%10
1. base -> n<=0 return 0;
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
