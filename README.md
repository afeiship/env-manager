# copy-selection-element
> Copy html from selection element.

[![version][version-image]][version-url]
[![license][license-image]][license-url]
[![size][size-image]][size-url]
[![download][download-image]][download-url]

## installation
```shell
npm install @jswork/copy-selection-element
```

## usage
```js
import copySelectionElement from "@jswork/copy-selection-element";

const el = document.querySelector(".content");
const successful = copySelectionElement(el);

if (successful) {
  // do somthing...
}
```

## license
Code released under [the MIT license](https://github.com/afeiship/i18n-helper/blob/master/LICENSE.txt).

[version-image]: https://img.shields.io/npm/v/@jswork/i18n-helper
[version-url]: https://npmjs.org/package/@jswork/i18n-helper

[license-image]: https://img.shields.io/npm/l/@jswork/i18n-helper
[license-url]: https://github.com/afeiship/i18n-helper/blob/master/LICENSE.txt

[size-image]: https://img.shields.io/bundlephobia/minzip/@jswork/i18n-helper
[size-url]: https://github.com/afeiship/i18n-helper/blob/master/dist/index.min.js

[download-image]: https://img.shields.io/npm/dm/@jswork/i18n-helper
[download-url]: https://www.npmjs.com/package/@jswork/i18n-helper
