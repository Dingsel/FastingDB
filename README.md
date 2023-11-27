# fastingDB
A modern way to store data in Minecraft Bedrock 1.20.x using DynamicProperties

##Creating a refference to a db:
```js
const db = new FastingDB()
//or assuming you have an entity you want to store the data to instead:
const db = new FastingDB(entity)
```

##Saving data:
```js
const db = new FastingDB()
//db.set(key, value)
db.set("someCounter", 6)
```

##Getting data:
```js
const db = new FastingDB()
//db.get(key)
db.get("someCounter") //6
```

##Clearing the whole db:
```js
const db = new FastingDB()

db.set("someCounter", 6)
db.set("someOtherCounter", 9)

//db.clear(void)
db.clear()

db.get("someCounter") //undefined
```

Feel free to add more exaples by contributing!
