bootstrap.servers=pkc-do3y7.us-central1.gcp.devel.cpdev.cloud:9092
ssl.endpoint.identification.algorithm=https
security.protocol=SASL_SSL
sasl.mechanism=PLAIN
sasl.jaas.config=org.apache.kafka.common.security.plain.PlainLoginModule required username="<CLUSTER_API_KEY>" password="<CLUSTER_API_SECRET>";
