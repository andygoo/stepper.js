# Stepper.js
jQuery library that aims to mimics the input[type=number] html5 functionality.

### Usage

```html
<!DOCTYPE html>
<body>
    <div class="js-spinner">
        <input type="number" step="1" max="10" min="0" class="js-stepper">
        <button type="button" spinner-button="up" title="add 1">+</button>
        <button type="button" spinner-button="down" title="subtract 1">-</button>
    </div>

    <script src="jquery.js"></script>
    <script src="stepper.js"></script>
</body>
```

### Options
```js
step:       "1",        // Amount to increment on each step. Also accepts decimals.
min:        "1000",     // Min amount
max:        "10",       // Max amount
debounce:   400,        // Time in milliseconds to debounce the change event
```

### Install
- **yarn:** `yarn add stepper.js`
- **npm:** `npm install --save stepper.js`

### CDN
- https://unpkg.com/stepper.js@1.0.2/dest/stepper.min.js

### Alternatives
- **https://github.com/vsn4ik/jquery.spinner