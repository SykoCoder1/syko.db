
**Syko.db | SykoCoder**

**Site:** https://sykocoder.tk

**NPM:** https://npmjs.com/package/syko.db

**Bug Report:** SykoCoder#4105

## Example

```js
const db = require("syko.db");

//Set Data
db.set("test", "testt")//set data
db.add("test1234", 100)// data add value

//Delete Data
db.delete("test123")// data delete

//Get Data
db.get("test")//get data
db.fetch("test")//fetch data
db.has("test")//has data

//Array Methods
db.set("test123", [])
db.push("test123", { test: "SykoCoder" })

//All Data
db.all()


 ```

 ## Installation

```
npm i syko.db
```
