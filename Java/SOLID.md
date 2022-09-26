# SOLID(OOP 5대 원칙)

## 단일 책임의 원칙(Single Responsibility Principle)

모든 Class는 하나의 책임만 가지며, 그 책임은 완전히 캡슐화되어야 한다. 그 클래스가 제공하는 서비스는 하나의 책임을 수행하는데 집중되어야 한다.

## 개방/폐쇄 원칙(Open/Closed Principle)

클래스, 모듈 함수 등의 소프트웨어 개체는 확장에 대해 열려있어야 하고, 수정에 대해서는 닫혀 있어야 한다는 프로그래밍 원칙이다.

## 리스코프 치환 원칙(Liskov Substitutions Principle)

부모 Class가 들어갈 자리에 자식 Class를 넣어도 잘 구동되어야 한다 라는 원칙이다.

## 의존성 역전 원칙(Dependency Inversion Principle)

1. 상위 모듈은 하위 모듈에 종속되어서는 안된다. 둘 다 추상화에 의존해야 한다.
2. 추상화는 세부사항에 의존하지 않는다. 세부사항은 추상화에 의해 달라져야 한다.
