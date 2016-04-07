#### モックライブラリ

モックとかスパイとかができる!

長くなるので割愛!

```javascript
// pray・show メソッドを持つ mock オブジェクトを作成
var mock = jasmine.createSpyObj('mock', ['pray', 'show']);

// pray メソッドを呼び出す
mock.pray();

// pray メソッドが呼び出されていることを検査
expect(mock.pray).toHaveBeenCalled();

// show メソッドは呼び出されていないことを検査
expect(mock.show).not.toHaveBeenCalled();
```
