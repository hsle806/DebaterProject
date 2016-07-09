# DebaterProject

## MongoDB Setting on Linux
1. Install MongoDB 
[$ sudo apt-get install -y mongodb-org]

2. Excute MongoDB
2-1. Check Version
2-2. Start 
[$ sudo service mongod start]
2-3. Stop
[$ sudo service mongod stop]
2-4. Restart
[$ sudo service mongod restart]



※ Specify Data Directory (Optional)
- Default: /data/db on Linux
- if you want to change a data directory
[$ mongod --dbpath "directory path"]