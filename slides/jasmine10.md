### ブラウザーで動かす

テストを実行するための HTML ファイルを作る

```html
<!DOCTYPE html>
<!-- spec.html -->
<html>
  <head>
    <meta charset="UTF-8" />
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jasmine/2.4.1/jasmine.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jasmine/2.4.1/jasmine-html.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jasmine/2.4.1/boot.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/jasmine/2.4.1/jasmine.css" />

    <script src="scripts/math.js"></script>
    <script src="spec/math.spec.js"></script>
  </head>
  <body>
  </body>
</html>
```
