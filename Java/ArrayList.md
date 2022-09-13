# ArrayList

```java
public class Main {

    public static void main(String[] args) {
        ArrayList pitches = new ArrayList();
        pitches.add(0, "1234");   //첫번째 위치에 1234 삽입
    }
}
```

## get

get 메소드를 이용하여 특정 인덱스값 추출

```java
System.out.println(pitches.get(0));

//1234
```

## size

size 메소드는 ArrayList의 갯수를 리턴

```java
System.out.println(pitches.size());

//1
```

## contains

contains 메소드는 리스트 안에 해당 항목이 있는지를 판별하여 그 결과를 boolean으로 리턴

```java
System.out.println(pitches.contains("1234"));

//true
```

## remove

remove 메소드에는 두가지 방식이 있다.(입력 파라미터가 다름)

### remove(객체)

리스트에서 객체에 해당되는 항목을 삭제하고 삭제한 결과(true, false)를 리턴

```java
System.out.println(pitches.remove("1234"));

//1234라는 항목이 삭제된다.
//true
```

### remove(인덱스)

해당 인덱스의 항목을 삭제하고 삭제된 항목을 리턴

```java
System.out.println(pitches.remove(0));

//1234
```
