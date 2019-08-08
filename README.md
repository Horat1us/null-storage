# Null Storage
![GitHub](https://img.shields.io/github/license/Horat1us/null-storage)
![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/Horat1us/null-storage)
![TypeScript Support](https://img.shields.io/badge/language-TypeScript-blue)

[Web Storage API](https://developer.mozilla.org/ru/docs/Web/API/Storage) implementation with no store effects.

May be used when storage not configured yet or inside Node.JS as placeholder.

## Installation
Using [npm](https://npmjs.com/package/null-storage)
```bash
npm i null-storage
```

## Example

```javascript
import { nullStorage } from "null-storage";

// Note: nothing will be saved!
nullStorage.setItem("key");
```

## Contributors
- [Alexander <horat1us> Letnikow](mailto:reclamme@gmail.com)

## License
[MIT](./LICENSE)
