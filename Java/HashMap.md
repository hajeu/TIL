# HashMap

## put

```java
import java.util.HashMap;

public class Sample {
    public static void main(String[] args) {
        HashMap<String, String> map = new HashMap<>();
        map.put("first", "1");
        map.put("second", "2");
    }
}
```

key와 value는 put메소드를 이용하여 입력

## get

```java
System.out.println(map.get("people"));

//1
```

get 메소드는 key에 해당하는 value를 얻기 위해 사용한다.
