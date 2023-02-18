# TANJIRO'S SIM-TEACH
This is a package that contains sim-teach commands directly from my API
[Tanjiro API](https://tanjiro-api.onrendeer.com)
[Tanjiro Sim-Teach API](https://simsimi-api.tanjirokamado0806.repl.co/)

## Installation

```bash
npm install tanjiro-sim-teach
```

## SIM
```js
const sim = require("tanjiro-sim-teach").sim,
  res = sim("hi");

console.log(res.ans) //OUTPUTS HELLO
```

## TEACH
```js
const teach = require("tanjiro-sim-teach").teach,
  res = teach("hi", "hello");
  // "hi" stands for your ask/question
  // "hello" stands for simsimi answer 

console.log(res.teach)
```