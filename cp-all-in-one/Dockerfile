FROM confluentinc/cp-kafka-connect:5.2.1
RUN confluent-hub install --no-prompt debezium/debezium-connector-mysql:1.2.0
COPY . .