# minecraft-map-colors

## Usage

```js
import { getColor } from '@aresrpg/aresrpg-map-colors'
```

Arguments and return value are memoized for performances

> We use a weighted aproach of the color space, read more on [Here](https://en.wikipedia.org/wiki/Color_difference)

```js
const colorId = MapColor.nearestMatch(70, 120, 35)
```
