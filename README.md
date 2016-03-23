# left-shark

It's like left-pad, except the examples have sharks.

## Installation

```
npm install --save left-shark
```

## Usage

```js
> const leftShark = require('left-shark')
> console.log(leftShark('|\\ ', 23))
                    |\
> console.log(leftShark('|\\ ', 23, '~'))
~~~~~~~~~~~~~~~~~~~~|\
```

## Wait, what?

This is using [`lodash.padstart`](https://www.npmjs.com/package/lodash.padstart) under the hood because [JDD said Sup](https://twitter.com/jdalton/status/712418254010986497).

