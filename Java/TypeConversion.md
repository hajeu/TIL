# 형변환

```java
public class main {
    public static void main(String[] args) {
        String num = "1122";
        int n = Integer.parseInt(num);
        System.out.println(n);  // 1122
    }
}
```

## final

final은 자료형에 값을 단 한번만 설정할 수 있게 하는 키워드이다.

```java
public class Sample {
    public static void main(String[] args) {
        final int n = 123;
        n = 456;  // error
    }
}
```
