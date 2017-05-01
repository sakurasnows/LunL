Kafka broker result:  
bigdata-0  
recovery-point-offset-checkpoint  
cleaner-offset-checkpoint  
replication-offset-checkpoint  
meta.properties

all docker machine started:  
CONTAINER ID        IMAGE                   COMMAND                  CREATED             STATUS              PORTS                                                                    NAMES

d9cee11fa057        confluent/kafka         "/usr/local/bin/ka..."   39 hours ago        Up 39 hours         0.0.0.0:9092->9092/tcp                                                   kafka

e6fa73b13b53        confluent/zookeeper     "/usr/local/bin/zk..."   40 hours ago        Up 40 hours         0.0.0.0:2181->2181/tcp, 0.0.0.0:2888->2888/tcp, 0.0.0.0:3888->3888/tcp   zookeeper

21fa1f4a212c        unclebarney/chit-chat   "node index.js"          40 hours ago        Up 40 hours         0.0.0.0:3000->3000/tcp 

Zookeeper Znode Data:

cZxid = 0x0  
ctime = Wed Dec 31 19:00:00 EST 1969  
mZxid = 0x0  
mtime = Wed Dec 31 19:00:00 EST 1969  
pZxid = 0x0  
cversion = 0  
dataVersion = 0  
aclVersion = 0  
ephemeralOwner = 0x0
dataLength = 0
numChildren = 0

Create Znode Data:

cZxid = 0x3  
ctime = Sun Apr 30 21:44:54 EDT 2017  
mZxid = 0x3  
mtime = Sun Apr 30 21:44:54 EDT 2017  
pZxid = 0x3  
cversion = 0  
dataVersion = 0  
aclVersion = 0  
ephemeralOwner = 0x0  
dataLength = 8  
numChildren = 0  

Ephemeral Znode Data:

cZxid = 0x6  
ctime = Sun Apr 30 21:46:56 EDT 2017  
mZxid = 0x6  
mtime = Sun Apr 30 21:46:56 EDT 2017  
pZxid = 0x6  
cversion = 0  
dataVersion = 0  
aclVersion = 0  
ephemeralOwner = 0x15bc1aae6f20001  
dataLength = 11  
numChildren = 0  

Watcher get:

unclebarney  
cZxid = 0x6  
ctime = Sun Apr 30 21:46:56 EDT 2017  
mZxid = 0x6  
mtime = Sun Apr 30 21:46:56 EDT 2017  
pZxid = 0x6  
cversion = 0  
dataVersion = 0  
aclVersion = 0  
ephemeralOwner = 0x15bc1aae6f20001  
dataLength = 11  
numChildren = 0  