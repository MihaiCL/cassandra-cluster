# cassandra-cluster
to run standalong container
docker run -d -p 7000:7000 -p 7001:7001 -p 7199:7199 -p 9042:9042 -p 9160:9160 -v /persistent/local/storage:/var/lib/cassandra --name csnd cassandra:2.2
