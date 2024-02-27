
<h3 align="center">
  
  <p align="center"><img src="https://img.shields.io/badge/WLCM%20TO -NAYAN SERVER-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">  
  
</h3>


<a href="https://www.npmjs.com/package/nayan-server"><img alt="npm version" src="https://img.shields.io/npm/v/nayan-server.svg?style=flat-square"></a>
<img alt="version" src="https://img.shields.io/github/package-json/v/MR-IMRAN-60/textpro-imran?label=github&style=flat-square">
<a href="https://www.npmjs.com/package/nayan-server"><img src="https://img.shields.io/npm/dm/nayan-server.svg?style=flat-square" alt="npm downloads"></a>

## Instalation :
```bash
> npm i textpro-imran
```

#### Available Api

```
• textpro
• photoxy
```

## Usage PHOTOXY
```js
const {photoxy} = require("textpro-imran");

const url = "url" // photoxy url

const text = "imran" // your text

  photoxy(url, [text])
.then((data) => console.log(data))
.catch((err) => console.log(err));
```
## Usaage Textpro
```JS
const {textpro} = require("textpro-imran");

const url = "url" // textpro url

const text = "imran" // your text

    textpro(url, [text])
.then((data) => console.log(data))
.catch((err) => console.log(err));
```
