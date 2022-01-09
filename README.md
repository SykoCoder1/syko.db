
**Syko.db | SykoCoder**

**Site:** https://sykocoder.tk

**NPM:** https://npmjs.com/package/syko.db

**Bug Report:** SykoCoder#4105

## Update's

- Backup System
- Update Data/Array
- Subtract Data
- Pull Array

## Example

```js
const Database = require("syko.db");

let db = new Database('./database.json', {
  backup: {
    enabled: true,
    time: 5000,
    path: './backups/'
  }
})

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
		console.log(a.test)
	}
})

//Find Data
db.set("asd", "test")

db.includes("test")

//Update Data
db.set("asd", {test: "sykocoder"})
db.update("asd", {asdasd: syko})

//Subtract Data
db.set("test123", [])
db.push("test123", { test: "SykoCoder", asd: "test" })
db.subtract("test123", "SykoCoder")

//Pull Array
db.set("Test", ['a', 'b', 'c', 'a', 'b', 'c'])
db.pull("Test", 'a')

//LowerCase Data
db.lowerCase("asd-asd-asd-asd")

//Array Methods
db.set("test123", [])
db.push("test123", { test: "SykoCoder", asd: "test" })
db.subtract("test123", "SykoCoder")


//All Data
db.all()

//Ping Data
db.ping()

//Info Data
db.size()
 ```

 ## Installation

```
npm i syko.db
```
