# 객체 지향(Object oriented)

## 객체 지향 프로그래밍(OOP)이란?

> 프로그램 구현에 필요한 객체를 파악해서 객체들의 역할을 정의하여서 객체들 간의 '상호작용' 을 통해 프로그램을 만드는 것이다.

```java
class Test{
    void Ptest(){
        System.out.println(1234);
    }
}

public class Sample {
    public static void main(String[] args) {
        Test test1 = new Test();  // test1 객체를 생성한다.
        Test test2 = new Test();  // test2 객체를 생성한다.

        test1.Ptest();
        test2.Ptest();
    }
}

// 1234
// 1234
```

## 객체 지향 프로그래밍의 장점

- 코드를 재사용하기 쉽다.

- 업그레이드가 쉽다.

- 디버깅이 쉽다.

- 보안성이 향상된다.

## 객체 지향 프로그래밍의 단점

- 절차 지향 프로그래밍에 비해 실행 속도가 느리다.

## 절차지향(Procedural Programming)이란?

> 물이 위에서 아래로 흐르는 것처럼 실행 순서가 정해져있어서 코드의 순서가 바뀌면 결과가 바뀔 수 있다.
