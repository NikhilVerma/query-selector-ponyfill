[![npm version](https://badge.fury.io/js/query-selector-ponyfill.svg)](https://badge.fury.io/js/query-selector-ponyfill)

# query-selector-ponyfill

**Note:** This is a fork of the excellent work done in https://github.com/webdriverio/query-selector-ponyfill but presented as a ponyfill which overrides the default querySelector behaviour. This will let you use your test libraries and other code behave as normal when working with Web components.

querySelector that can pierce Shadow DOM roots without knowing the path through nested shadow roots. Useful for automated testing of Web Components e.g. with Selenium, Puppeteer.

```js
import "query-selector-ponyfill";

// Now your document.querySelector* calls can pierce shadow roots
```

Please read the rest of the readme on: https://github.com/webdriverio/query-selector-shadow-dom
