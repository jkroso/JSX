# JSX-to-JS

Transpile JSX to JS. Unlike other implementations it keeps track of the variable scope and uses this to determine whether or not to convert the tag to a string. Other implementations just test if the tag's name is all lowercase.

## Installation

`npm install jsx-to-js`

then in your app:

```js
const JSX = require('jsx-to-js')
```

## API

```js
JSX(parse('<div/>')) // => parse('JSX("div")')
```
