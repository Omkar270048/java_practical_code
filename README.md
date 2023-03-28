# java_practical_code

add two binary numbers
```java
public class addBinaryNum {
    public static void main(String args[]){
        String x = "101010", y = "101010";
        int num1 = Integer.parseInt(x,2);
        int num2 = Integer.parseInt(y,2);
        int sum = num1 + num2;
        String result = Integer.toBinaryString(sum);
        System.out.print(result);
    }
}
```

Decimal to Binary converion
```java
public class decimalToBinary{
    public static void main(String args[])
    {
        int num = 5;
        System.out.print(Integer.toBinaryString(num));
    }

}
```
Reverse a string
```java
public class stringReverse {
    public static void main(String args[])
    {
        String s = "omkar";
        String rev = "";
        for(int i=0; i<s.length(); i++) {
        	rev = s.charAt(i) + rev;
        }
        System.out.println(rev);
    }
}
```

Find small & large element in an array
```java
import java.util.Arrays;

public class P6A {
    public static void main(String args[])
    {
        int num[] = {45,23,56,12,67,23,11,3};
        Arrays.sort(num);
        System.out.println("small : " + num[0]);
        System.out.println("large : " + num[num.length-1]);
    }
}

```
