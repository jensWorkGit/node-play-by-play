show dbs
use cats
show collections
db.cats.find()
db.cats.find({name: 'john'})
db.cats.find({name: 'john', age: 18})


npm install -g forever