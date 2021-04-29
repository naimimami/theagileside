

# Finite State Machine
```java
public enum FiniteStateMachine {
  Locked {
        @Override
        public void performActivity() {
            // TODO - Implement Activity
            System.out.println("\t ... working ... ");
        }

        @Override
        public Map<String, DoorFSM> getMap() {
            return new HashMap<>() {{
                put("Unlock", FiniteStateMachine.Unlocked);
            }};
        }
    },
    Unlocked {
        @Override
        public void performActivity() {
            // TODO - Implement Activity
            System.out.println("\t ... working ... ");
        }

        @Override
        public Map<String, DoorFSM> getMap() {
            return new HashMap<>() {{
                put("Open", FiniteStateMachine.Opened);
                put("Lock", FiniteStateMachine.Locked);

            }};
        }
    }
    protected abstract void performActivity();
}
```












# Docker & MariaDB (This is working)
```bash
docker ps -a
docker pull mariadb/server:10.4
docker run -p 3306:3306 -d --name mariadb-server -e "MARIADB_ROOT_PASSWORD=root" mariadb/server:10.4
docker ps
docker exec -it mariadb-server bash
mariadb --host 127.0.0.1 -P 3306 --user root -proot

CREATE DATABASE todo;
use todo;
CREATE TABLE tasks (
  id varchar(80) NOT NULL,
  description VARCHAR(500) NOT NULL,
  completed BOOLEAN NOT NULL DEFAULT 0,
  PRIMARY KEY (id)
);
```
# Docker & Cassandra Steps (This is working)
```bash
docker ps -a
docker stop cassandra-theagileside
docker rm cassandra-theagileside

docker pull cassandra:latest

docker run --name cassandra-theagileside -d \
    -e CASSANDRA_BROADCAST_ADDRESS=127.0.0.1 \
    -p 7000:7000 \
    -p 9042:9042 \
    --restart always\
    cassandra:latest

docker exec -it cassandra-theagileside bash

cqlsh

use my_keyspace;
select * from video;
select * from book;
select * from party;
```
