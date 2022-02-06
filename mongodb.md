# MongoDB online editor
Write, Run & Share MongoDB queries online using OneCompiler's MongoDB online editor and compiler for free. It's one of the robust, feature-rich online editor and compiler for MongoDB. Getting started with the OneCompiler's MongoDB editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'MongoDB' and start writing queries to learn and test online without worrying about tedious process of installation.

# About MongoDB

MongoDB is a cross platform document oriented NoSQL database. 

### Key Features:

* Designed to overcome the the limitations of relational databases approach and other NoSQL solutions
* Horizontal scaling 
* Load balancing capabilities
* Better data availability and stability 

# Syntax help

## Commands

### Inserting documents

1. `db.collection.insert()`: Using `insert` you can either insert one document or array of documents 
```json
db.cars.insert({  "name" : "Volvo xc 60",  "type" : "SUV" });
```

2. `db.collection.insertOne()`: Inserts one document 
```json
db.cars.insertOne({  "name" : "Volvo xc 60",  "type" : "SUV" });
```

3. `db.collection.insertMany`: Inserts multiple documents
```json
db.cars.insertMany(
 [
   { "name" : "Volvo xc 60",  "type" : "SUV" },
   { "name" : "Volvo xc 90",  "type" : "SUV" },
   { "name" : "Volvo S90",  "type" : "SUV" }
 ]
);
```

### Updating documents 

1. `db.collection.update()` : Updates one or more than one document(s) in collection based on matching document and based on `multi` option

```json
db.cars.update(
  { type: "SUV" },
  { $set: { size : 5} },
  { multi: true}
)
```
2.  `db.collection.updateOne()` : Updates a single document in collection based on matching document 
```json
db.cars.updateOne(
  { type: "SUV" },
  { $set: { size : 5} }
)
```
3.  `db.collection.updateMany()` : Updates multiple documents in collection based on the condition.
```json
db.cars.updateMany(
  { type: "hatchback" },
  { $set: { size : 5} }
)
```

### Deleting documents

1. `db.collection.deleteOne(<filter>, <options>)`: Deletes a Single document from collection
```json
db.employees.deleteOne({_id: 1})
```

2. `db.collection.deleteMany(<filter>, <options>)`: Deletes all documents with matching filter
```json
db.employees.deleteMany({type: "hatchback"})
```
