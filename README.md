# 340-CANVAS

```html
<canvas id="canvas" width="150" height="150"></canvas>
```
```js
const canvas = document.getElementById("canvas");
const ctx = canvas.getContext("2d");

```
#### Rect
```js
ctx.fillRect(25, 25, 100, 100);
ctx.clearRect(45, 45, 60, 60);
ctx.strokeRect(50, 50, 50, 50);
```
#### Triangle
```js
// Filled triangle
ctx.beginPath();
ctx.moveTo(25, 25);
ctx.lineTo(105, 25);
ctx.lineTo(25, 105);
ctx.fill();

// Stroked triangle
ctx.beginPath();
ctx.moveTo(125, 125);
ctx.lineTo(125, 45);
ctx.lineTo(45, 125);
ctx.closePath();
ctx.stroke();
```

### ZADANIA
ZAD34001 - Wypełnij canvas gradientem zbudowanym z prostokątów (jak poniżej) tak aby skalował się wraz z wielkością elementu (canvas)


### Tutorials

https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial?retiredLocale=pl
