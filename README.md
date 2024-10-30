# crc64-ecma

Calculate CRC64/XZ hashes for NodeJS.

**The module name is `crc64-ecma` but it uses the [CRC64/XZ algorithm](https://reveng.sourceforge.io/crc-catalogue/17plus.htm#crc.cat.crc-64-xz).**

## Installation

`npm install crc64-ecma`

## Usage

```js
import { crc64 } from 'crc64-ecma';

const data = 'Hello';
const crc = crc64(data);
// Output: 51cf5c3bc87bacc8
console.log(crc.toString(16));
```

## License

[GPL v2](LICENSE)
