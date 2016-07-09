# DebaterProject

### MongoDB Setting on Linux
##### 1. Install MongoDB
```
$ sudo apt-get install -y mongodb-org
```
##### 2. Excute MongoDB
- Check Version
```
$ mongo –version
```
- Start 
```
$ sudo service mongod start
```
- Stop
```
$ sudo service mongod stop
```
- Restart
```
$ sudo service mongod restart
```


※ Specify Data Directory 
- Default: /data/db on Linux
- if you want to change a data directory (Optional)
```
$ mongod --dbpath "directory path"
```
