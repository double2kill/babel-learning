# babel-plugin-babel-plugins



## Example

**In**

```js
// input code
```

**Out**

```js
"use strict";

// output code
```

## Installation

```sh
$ npm install babel-plugin-babel-plugins
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["babel-plugins"]
}
```

### Via CLI

```sh
$ babel --plugins babel-plugins script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["babel-plugins"]
});
```
