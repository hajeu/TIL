# readdir

## readdir는 파일의 목록을 배열로 가져온다.

```javascript
var fs = require("fs"); // 모듈 가져오기

var dir = "./test"; //파일 목록을 읽어올 폴더

fs.readdir(dir, function (err, filelist) {
  // fs모듈의 readdir함수를 사용해
  // 첫번째 인자로 파일 목록을 읽을 폴더(dir)를 가져오고
  // 콜백함수의 두번째 인자로 폴더(dir)의 파일목록(filelist)을 가져옴

  console.log(filelist);

  //출력
  //['file1', 'file2', 'file3']
});
```
