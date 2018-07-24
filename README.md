# Canvas-Signature-Jquery-Plugin
A Smooth Canvas Signature with Jquery and HTML 5.

#### Gallery Plugin
![Alt text](screenshot.png?raw=true "Template Preview")

#### Usage

```html
<canvas id="myCanvas"></canvas>
<input type="button" value="Reset" id='resetSign'>
```

```js
$(document).ready(function() {
    $('#myCanvas').sign({
        resetButton: $('#resetSign'), // Reset input * optional
        lineWidth: 5, // * Optional
        width: 300, // * optional. Default: 500
        height: 250, // * optional. Default: 300
    });
});
```

#### Require
jQuery 1.3+
