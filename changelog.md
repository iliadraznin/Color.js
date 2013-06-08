# Color.js

### 1.6 (June 08, 2013)
- Fixed in `calcRGBfromHSV()` reference to non-existent `hsl2rgb()`, it's now `hsv2rgb()`
- In rgb2hsv() fixed the first return to adjust the `saturation` and `value` values
- Changed `fourToArray()` to `toColorsArray()`
- `toColorsArray()` provides now a more robust handling of input, including arrays
- Colors can now be created using HSV values as well (if the first "r" value is more than 255)

### 1.4 (June 06, 2013)
- Added functions to convert between HSV and HSL
- Added functions to output Color to CSS formatted rgba() and hsla() strings

### 1.1 (June 06, 2013)
- Corrected HSL to HSB

### 1.0 (June 05, 2013)
- Initial release