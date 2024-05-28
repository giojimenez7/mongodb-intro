## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://gio:gio123@mongodb101.vyxeond.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("store")
db.products.find()
```
