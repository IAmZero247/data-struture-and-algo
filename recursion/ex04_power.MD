# Power

 -  base and exponent 
   
 -  3^2
  
 -  3 is base and 2 is exponent


## Java 


1. flow -> power(base, exponent) = base * power(base, exponent-1)
1. base -> when exponent = 0 return 1
1. unintentional-> base or exponent < 0 return -1

```java
   public static int power(int b, int e) {
      if (b <0 || e <0){
       return -1;
      }
     
      if (e == 0){
       return 1;
      }
     
      return b * power(b, e-1);
   }
```
