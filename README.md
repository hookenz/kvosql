# KVoSQL
Key Value over SQL

# What is this?
Sometimes you have a key value store such as BoltDB etc and you have a desire to move switch away from boltdb to e.g. sqlite
The boltapi is a fine interface and is fairly generic.  SQLite is an easy to work with sql library.
This library is going to be my attempt at taking the bolt API and placing it overtop of sqlite

# Why would you do that?
Databases like boltdb are awesome and very fast.  SQLite is also very fast too.  In some projects where a KV store is used, users would prefer to swap out the KV database and work with a sql databases.  In the case of SQLite, I'm interested in swapping out a boltdb and inserting in SQLite so that I can use Litestream without changing the code.

Having built a kv store on mysql some years ago that never saw the light of day and recalling how simple it was.  This is my attempt to revive it and make it something useful. 

