# java_practical_code

add two binary numbers
```java
public class addBinaryNum {
    public static void main(String args[])
    {
        String x = "101010", y = "101010";
        int num1 = Integer.parseInt(x,2);
        int num2 = Integer.parseInt(y,2);
        int sum = num1 + num2;
        String result = Integer.toBinaryString(sum);
        System.out.print(result);
    }

}

```
