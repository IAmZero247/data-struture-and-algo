
# Sum Of Digits 

- n = 15 -> 1+5 = 6
- n = 99 -> 9+9 = 18

- n= 789 -> 7+8+9=24 

```
  Logic 
  1. Divide by 10 , get remainder 
  2. Divide quotient by 10  until the quotient is 0, get remainder each time and do summation 
  3. when quotient is 0 return 0


   For Eg 
   789 -> q=78 r=9
          q=7  r=8
          q=0  r=7
          ........
                 9+8+7=24
```
## Java 


1. flow -> sumOfDigits(n) = sumOfDigit(n/10) + n%10
1. base -> n=0 return 0
1. unintentional-> n<0 return -1

```java
 public static int sum(int n) {
      if (n <0){
       return -1;
      }
     
      if (n == 0){
       return 0;
      }
     
      return sum(n/10) + n%10;
   }
```
