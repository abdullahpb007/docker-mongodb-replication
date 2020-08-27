# docker-mongodb-replication

> docker-compose up -d
> docker ps (to check whether all instance are live)
> docker exec -it {instance_name} mongo
> rs.initiate();rs.add('mongo-2.myrepl');rs.addArb('mongo-3.myrepl');
> rs.status() (to check whether replication set is initiated)
