# MongoDemo

use rest_tutorial;
db.createCollection("pets")
db.rest_tutorial.insertOne({"name":"Spot","species":"dog","breed":"ptibull"})
db.getCollection('pets').find({species:"dog"},{breed:1})
