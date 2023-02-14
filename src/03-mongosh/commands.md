## connect to container

```sh
docker-compose exec mongodb bash
```

## Conect with mongosh

```sh
mongosh "mongodb://root:example@localhost:27017/?authMechanism=DEFAULT&tls=false"
```

```sh
show dbs
show collections
```

```sh
use('platzi_products')
db.products.find()
```
