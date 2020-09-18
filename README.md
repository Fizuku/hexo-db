# hexo-db
An NPM Package helper to let you interact with your HexoShard database.

## What is HexoDB?
An easy external database for your small projects, like Discord bots!
HexoDB is:
* Easy Connection
* Simple
* Fast read and writing data

## Getting Started
If you're interested to get your own database, you may visit our site by clicking [here](https://hexodb.glitch.me/)

## Example
```js
const Hexo = require("hexo-db");
const db = new Hexo.Database("https://db--username.repl.co")

db.set("foo", "bar")
.then(() => console.log("ID 'foo' is saved with the value 'bar'!"));

db.get("foo").then(data => {
  console.log(data) // Logs 'bar'
});
```

## Built with
* [superagent](https://npmjs.com/package/superagent) - used to scrape your data!
* [Glitch](https://glitch.com/) - HexoDB started out here!
* [Repl.it](https://repl.it) - your HexoShard is hosted here!

## Authors
**Fizx** - *Initial work* - [Fizuku](https://github.com/Fizuku/)

## License
This project is licensed under the Apache License 2.0 - see [LICENSE.md](LICENSE.md)
for details.

## Support
You may contact me on Discord! (Fizx#5360)
