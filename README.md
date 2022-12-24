<div align="center">
  <a href='https://ciff.js.org'>
    <img witdh="300" src="https://user-images.githubusercontent.com/104754516/208326173-18c4e5b1-1857-4e09-8d23-fc377f8ee32e.jpg">
    <h1>Ciff.js</h1>
  </a>
  <b>Building API easy and simple with Ciff.js!</b><br>
  v1.0.1
</div>

## Feature
- Easy to learn
- Simple

## Install
```npm i ciff.js``` ```yarn add ciff.js```
## SetUp
```js
const { API } = require("ciff.js");

const api = new API({
  port: 3000, //default port or use your port.
});

api.route.add({
  path: "/",
  code: `
    console.log('Hello World')
  `
})

api.deploy() // deploy your API.
```

## 🔗 Link
- [GitHub](https://github.com/MonoeDev/ciff.js)
- [NPM](https://npmjs.com/package/ciff.js)
- [Discord](https://discord.gg/INVALID)

