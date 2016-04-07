### 簡単な使い方

スクリプトを作成

```javascript
// google.js

var page = require('webpage').create();

page.open('https://www.google.co.jp', function () {
  page.render('google.png');

  phantom.exit();
});
```
