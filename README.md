# jp-color-palette
Color palettes defined in "Traditional Japanese Color Palette" from PIE Books

## Usage
```javascript
// default export is an array of "palettes"
import palettes from '@eatspaint/jp-color-palette';
const random = require('canvas-sketch-util/random');

// each "palette" is an array of hexidecimal color codes (generally 2-6 codes per palette)
const palette = random.pick(palettes);

palette.forEach((color) => {
  // DO COLORFUL THINGS
});
```
