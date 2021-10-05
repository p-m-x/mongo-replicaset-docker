# mongo-replicaset-docker

### Set Mongo data volume directory
```
$ export MONGO_VOL_DIR=~/
```

### Run script to create replicaset
```
$ ./docker.sh
```

### Add in your hosts
```
127.0.0.1 mongo1 mongo2 mongo3
```

### Connect to replicaset
```
mongodb://localhost:27017,localhost:27018,localhost:27019/<DBNAME>
```