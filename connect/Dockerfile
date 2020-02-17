FROM confluentinc/cp-kafka-connect:5.4.0

RUN rm /usr/share/java/kafka-connect-ibmmq/connect-transforms-5.4.0-ce.jar \
       /usr/share/java/kafka-connect-activemq/connect-transforms-5.4.0-ce.jar \
       /usr/share/java/confluent-control-center/connect-transforms-5.4.0-ce.jar \
       /usr/share/java/confluent-rebalancer/connect-transforms-5.4.0-ce.jar
RUN confluent-hub install --component-dir /usr/share/confluent-hub-components --no-prompt confluentinc/kafka-connect-cassandra:1.2.0
RUN confluent-hub install --component-dir /usr/share/confluent-hub-components --no-prompt jcustenborder/kafka-connect-spooldir:1.0.41
