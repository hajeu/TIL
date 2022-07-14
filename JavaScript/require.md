# require

## require 메서드는 외부 모듈을 가져올 때 사용된다.

```js
//test.js
console.log("JavaScript");
```

```js
//main.js
require(./test.js); // 출력 JavaScript
```

 require로 모듈을 가져와도 해당 모듈의 API에 접근할 권한이 바로 생기지 않는다.

## 모듈(module)이란?

> 기능들에 관한 코드가 모여있는 하나의 '파일'이다.

## API란?

> 프로그램들이 서로 상호작용할 수 있게 도와주는 매개체이다.s