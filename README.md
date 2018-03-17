# extracting-data-from-mongo-db
Mongo Db
#See the exesting databases

show dbs

#Creating a new collection in thedb

db.createCollection('modi')

#Inerting the Data into the Collection

db.modi.insert({'bio':{'name': 'Narendra Modi','job':'Prime Minister'}})

#Checking the collections

show collections

#Querying the collection

db.modi.find()

#Inserting a new record

db.modi.insert({'bio':{'name': 'Rahul Gandhi','job':'Congress President'}})

#Checking the Entire collection


db.modi.find()

#Inserting one more row into the modi collection

db.modi.insert({'name': 'kcr'job':'TG cm'})

#Checking the collection

#db.modi.find()

#Querying by name

db.modi.find({'name':'kcr'})

