# RGB to HSL and back again...

run `npm install`

run `npm run build`

## Example

```typescript
import RgbToHsl from "@orderandchaos/rgb-to-hsl";
const rgbToHsl = new RgbToHsl();
rgbToHsl.fromRgbHex(0x0000ff)

console.log(rgbToHsl.r);
console.log(rgbToHsl.g);
console.log(rgbToHsl.b);

console.log(rgbToHsl.h);
console.log(rgbToHsl.s);
console.log(rgbToHsl.l);
console.log(rgbToHsl.rgb);
rgbToHsl.h += 180;
console.log(rgbToHsl.rgb);
rgbToHsl.h += 180;
console.log(rgbToHsl.rgb);
```
