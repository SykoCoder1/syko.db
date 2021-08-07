
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

//Get Data
db.get("test")//get data
db.fetch("test")//fetch data
db.has("test")//has data

//Delete Data
db.delete("test123")// data delete

//Filter Data
var test = [
  { test: 'test', test3: "test3"},
  { test2: 'test2',   test4: "test4"}
]

db.set("data", test)//set array data

db.filter("data").forEach(a => {
	if(a.test === "test") {
		console.log(a.test3)
	}
})

//Find Data
db.set("asd", "test")

db.includes("test")

//LowerCase Data
db.lowerCase("asd-asd-asd-asd")

//Array Methods
db.set("test123", [])
db.push("test123", { test: "SykoCoder" })

//All Data
db.all()


//Info Data
db.size()
 ```

 ## Installation

```
npm i syko.db
```
