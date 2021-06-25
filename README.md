# mongodb
mongodb

```
$ alias mg_start="brew services start mongodb/brew/mongodb-community"
$ alias mg_stop="brew services stop mongodb/brew/mongodb-community"
$ alias mg_restart="brew services restart mongodb/brew/mongodb-community"
```

To run MongoDB (i.e. the mongod process) manually as a background process, issue the following:
```
mongod --config /usr/local/etc/mongod.conf --fork
brew services list
ps aux | grep -v grep | grep mongod
```
