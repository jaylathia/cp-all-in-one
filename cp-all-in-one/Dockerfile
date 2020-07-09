FROM confluentinc/cp-kafka-connect:5.2.1
RUN confluent-hub install --no-prompt debezium/debezium-connector-mysql:1.2.0
#RUN confluent-hub install --no-prompt confluentinc/kafka-connect-jdbc:5.5.1
#COPY mysql-connector-java-8.0.20.jar /usr/share/java/kafka-connect-jdbc
COPY . .