
# color

  super basic color tinter. Based on an answer to the SO question: [Programmatically darken a Hex colour](http://stackoverflow.com/a/1787140/145435)

## Installation

    $ component install matthewmueller/color

## Example

```js
var color = require('color'),
    c = '#C8272B';

color.darken(c, .5) // '#643d39'
color.lighten(c, .5) // '#fa595d'
```

## API

### darken(color, val)

  Darkens the `color` by the given `val`.

### lighten(color, val)

  Lightens the `color` by the given `val`.

## License

  MIT
