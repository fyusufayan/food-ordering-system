In order to boot the application follow the given instructions:

Under /infrastructure/docker-compose

1. docker-compose -f common.yml -f zookeeper.yml up
2. docker-compose -f common.yml -f kafka_cluster.yml up
3. docker-compose -f common.yml -f init_kafka.yml up
