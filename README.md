
**Syko.db | SykoCoder**

**Site:** https://sykocoder.tk

**NPM:** https://npmjs.com/package/syko.db

**Bug Report:** SykoCoder#4105

## Example

```
const db = require("syko.db");

//

//Set Data
db.set("test", "testt")//set data

//All Data
db.all()

//Get Data
db.get("test")//get data
db.fetch("test")//fetch data
db.has("test")//has data

//Array Methods
db.set("test123", [])
db.push("test123", { test: "SykoCoder" })

db.add("test1234", 100)// data add value

db.delete("test123")// data delete

 ```

 ## Installation

```
npm i syko.db
```
