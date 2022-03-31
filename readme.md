# MongoDB Master

## What is MongoDB?
=> 
    1. Documents based database system
    2. Stores data as JSON-like format

`Example: `
{
    name: "Samiul",
    age: 23,
    languages: ["English", "Bangla", "Hindi"]
}

## RDBMS VS MongoDB Terms:
    1. Database = database
    2. Tabels = collections
    3. Rows = documents
    4. Columns = fields

`Run The Mongoshell` - mongo + enter
`help`
`Databases:`
    show dbs
    create and switch database: use databaseName
    check which database you are in: db + enter
    delete database: db.dropDatabase()

`Collection:`
    show collections
    db.createCollection(name, options)

### Create data

`Insert data to collection:`
db.collectionName.insertOne() => for insert single document

db.collectionName.insertMany([]) => for insert multiple document

### Read Data

`See all data: ` db.collectionName.find()

`See all data with formating: ` db.collectionName.find().pretty()

`See specific data: ` db.collectionName.find(name: 22) => inside find method pass the condition

`See limited data with condition: ` db.collectionName.find(name: 22).limit(limit range).pretty()

### Update Data

`Update document: ` db.collectionName.update({condition}, {$set: {updated data}} )

### Delete Data

`Delete document: ` db.collectionName.deleteOne(option or condition like => name: "Samiul Islam")

## MongoDB Compas








