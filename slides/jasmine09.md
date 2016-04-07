### ブラウザーで動かす

```javascript
// scripts/math.js

// テスト対象関数
var math = {
  add: function (x, y) {
    return x + y;
  }
};
```

```javascript
// spec/math.spec.js
describe('math.add()', function () {
  it('1 + 2 = 3', function () {
    expect(math.add(1, 2)).toEqual(3);
  });
});
```
