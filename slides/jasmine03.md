### 簡単な使い方

テスト対象とテストコードを書く

```javascript
// math.js

// テスト対象関数
function add(x, y) {
  return x + y;
}

module.exports = {add: add};
```

```javascript
// spec/math.spec.js
var math = require('../math');

// テストコード
describe('math.add()', function () {
  it('1 + 2 = 4', function () {
    expect(math.add(1, 2)).toEqual(4);
  });
});
```
