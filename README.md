# mongodb
mongodb

Install the Xcode command-line tools by running the following command in your macOS Terminal:
```
xcode-select --install
```

Tap the MongoDB Homebrew Tap to download the official Homebrew formula for MongoDB and the Database Tools, by running the following command in your macOS Terminal:
```
brew tap mongodb/brew
```
To install MongoDB, run the following command in your macOS Terminal application:
```
brew install mongodb-community@4.4
```

Create alias for mongodb start program:
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

To begin using MongoDB, connect a mongo shell to the running instance. From a new terminal, issue the following:
```
mongo
mongotop
```
