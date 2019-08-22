# canvas-draw

![License MIT](https://img.shields.io/npm/l/express.svg)

## How to use
```html
<canvas id="canvasBox" style="width: 400px;height: 400px"></canvas>
<button onclick="downloadDraw()">download</button>
<!--just for dev-->
<script src="http://s.ljb.work/libs/draw-es5.js"></script>

<script>
    const canvas = document.getElementById('canvasBox');
    var draw = new Draw(canvas);
    
    function downloadDraw() {
      draw.downloadPNGImage(draw.getPNGImage());
    }
</script>

```

## More detail

更多详情请查看原始ropo。

## License

Released under [MIT](http://rem.mit-license.org/)  LICENSE。
