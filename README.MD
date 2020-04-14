# minecraft-map-colors

## Usage

Arguments and return value are memoized for performances

> We use a weighted aproach of the color space, read more on [Here](https://en.wikipedia.org/wiki/Color_difference)

```js
import { getColor } from '@wvffle/minecraft-map-colors'
const colorId = getColor(70, 120, 35)
```
