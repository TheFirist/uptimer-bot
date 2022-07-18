# uptimer-bot


- 🤔 Uptimer-bot e  bot para hospedagem de websites/bots que são criados na replit utilizando a npm express
##


- 😁 Como usar

Primeiro crie seu projeto na [Replit](https://replit.com/)

Abra o terminal e utilize

```js
npm install express
```


Depois no seu arquivo principal coloque

```js
const express = require('express')
const app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
```

##

Express Info;
https://www.npmjs.com/package/express
