# node-day11-express-stater

- `Terminal`

```sh=
node app.js
```

---

## Notes

1. new project

2. `Terminal`

```sh=
npm init -y
```

```sh=
npm i express --save
```

3. new `app.js`

```JS=
const express = require('express');
const app = express();
```

4. `JS`-`port`

```JS=
const port = 3000;
app.listen((port), () => {
  console.log(`
    Listening on port::: ${port}
  `)
})
```

5. `JS`-`route`

```JS=
app.get('/', (req, res) => {
  res.send('Hello!')
})
```

6. `Terminal`-`run`

```sh=
node app.js
```

7. visit

```sh=
http://localhost:3000/
```

> [Edit on StackBlitz ⚡️](https://stackblitz.com/edit/node-r6zkk3)
