# HashMap

## put

key와 value는 put메소드를 이용하여 입력

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

## get

get 메소드는 key에 해당하는 value를 얻기 위해 사용

```java
System.out.println(map.get("first"));

//1
```

## containsKey

containsKey 메소드는 Map에 해당 Key가 있는지를 조사하여 그 결과값을 리턴

```java
System.out.println(map.containsKey("first"));

//true
```

## remove

remove 메소드는 Map의 항목을 삭제하는 메소드로 key값에 해당되는 Value를 삭제한 후 그 value 값을 리턴

```java
System.out.println(map.remove("first"));

//1
```

## size

size 메소드는 Map의 갯수를 리턴

```java
System.out.println(map.size());

//1
```

## keySet

keySet 메소드는 맵의 모든 key를 모아서 리턴

```java
import java.util.HashMap;

public class Sample {
    public static void main(String[] args) {
        HashMap<String, String> map = new HashMap<>();
        map.put("first", "1");
        map.put("second", "2");
        System.out.println(map.keySet());   // [first, second]
    }
}
```
