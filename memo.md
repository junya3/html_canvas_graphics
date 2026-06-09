## 度数法の度数からラジアンを参照算出する例

もしラジアンから変換して設定したい場合に使える。

```
let degrees = 45; // 45度

let radian = degToRad(degrees); // ラジアン

function degToRad(degrees) {
  return (degrees / 360) * (Math.PI * 2);
}
```
