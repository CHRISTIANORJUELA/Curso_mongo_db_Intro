## Connect to container

"""
docker-compose exec mymongodb bash
"""

## Connect with mongosh

"""
mongosh "<url connection>"

local:
mongosh "mongodb://root:root123@localhost:27017/?tls=false&authMechanism=DEFAULT"

Nube:
mongosh "mongodb://christian07:christian07@ac-rpj3hcb-shard-00-00.pl11fdo.mongodb.net:27017,ac-rpj3hcb-shard-00-01.pl11fdo.mongodb.net:27017,ac-rpj3hcb-shard-00-02.pl11fdo.mongodb.net:27017/?replicaSet=atlas-geajrp-shard-0&ssl=true&authSource=admin"
"""

## Some commands

"""
show dbs
show collections
"""


