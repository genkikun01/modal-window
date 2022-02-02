# モーダルウィンドウを作る！
## htmlを書きます

```html
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Modal</title>
</head>
<body>
<!-- クリックしたらモーダルを表示するボタン -->
<button class="btn">モーダルウィンドウを表示</button>

<!-- オーバーレイ -->
<div class="overlay"></div>

<!-- モーダルウィンドウ -->
<div class="modal">
  <div class="close">X</div>
  <div class="other">- ⬜</div>
    <h2>モダルのタイトル</h2>
    <p>ここにモダルの内容が入ります。ここにモダルの内容が入ります。ここにモダルの内容が入ります。ここにモダルの内容が入ります。ここにモダルの内容が入ります。ここにモダルの内容が入ります。</p>
</div>

<!-- スクロールで高さを出すためのsectionタグ -->
<section></section>

    <script src="index.js"></script>
  </body>
</html>
```
