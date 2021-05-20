
**Syko.db | SykoCoder**

**Site:** https://sykocoder.tk

**NPM:** https://npmjs.com/package/syko.db

**Bug Report:** SykoCoder#4105

## Example

```
const SykoCoder = require("syko.db");

let data = SykoCoder.get("SykoCoder")

SykoCoder.set("test", "testt")//set data

//Array Methods
data.push("test")
data.push({ test: "SykoCoder" })

data.add(100)// data add value

data.delete()// data delete

/////////////////////////////////////////////////////

SykoCoder.set("test", "testt")// set data

SykoCoder.push("test", "testt")
SykoCoder.push("test", { test: "SykoCoder" })

SykoCoder.add("test", 100)// data add value

SykoCoder.delete("test")// data delete
 ```

 ## Installation

```
npm i syko.db
```
