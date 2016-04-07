### 簡単な使い方

気を取り直して書きなおして!

```javascript
// spec/math.spec.js
var math = require('../math');

// テストコード
describe('math.add()', function () {
  it('1 + 2 = 3', function () {
    expect(math.add(1, 2)).toEqual(3);
  });
});
```
