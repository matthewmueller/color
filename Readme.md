
# color

  Extremely basic color tinting component. Based on an answer to the SO question: [Programmatically darken a Hex colour](http://stackoverflow.com/a/1787140/145435)

## Installation

    $ component install matthewmueller/color

## Example

```js
var color = require('color'),
    c = 'red';

color.darken(c, .5) // '#ff3232'
color.lighten(c, .5) // '#cd3232'
```

## API

### darken(color, val)

  Darkens the `color` by the given `val`.

### lighten(color, val)

  Lightens the `color` by the given `val`.

## License

  MIT
