# jquery-pixelate.js

Extensible jQuery plugin for pixelating images.

# Getting Started

Include jQuery and pixelate.js:

```html
<script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
<script src="assets/js/pixelate.js"></script>
```

Apply the `pixelate()` function to selected elements like so:

```js
$(document).ready(function() {
    $('.pixelate').pixelate();
});
```

# Options

- `focus` takes a value from 0 to 1 where the pixel density becomes larger as `focus` approaches 0. Default value: `0.5`.
- `canvasID` takes a string which designates the ID to be applied to the generated canvas element. Default value: `pixelateCanvas`.

## Overrides

Options can be overridden like so:

```js
$(document).ready(function() {
    $('.pixelate').pixelate({
        'focus': 0.75,
        'canvasID': "newCanvasID"
    });
});
```

# Credit

Groundwork by [jmduke](https://github.com/jmduke/jquery.pixelate.js).

# License

[MIT License](LICENSE)