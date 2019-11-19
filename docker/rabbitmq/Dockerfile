FROM rabbitmq:3.8.1-alpine
RUN rabbitmq-plugins enable --offline rabbitmq_mqtt rabbitmq_federation_management rabbitmq_stomp
# ADD ./docker/rabbitmq/rabbitmq.conf /etc/rabbitmq/
# ADD ./docker/rabbitmq/definitions.json /etc/rabbitmq/
# RUN chown rabbitmq:rabbitmq /etc/rabbitmq/rabbitmq.conf /etc/rabbitmq/definitions.json
# RUN cat /etc/rabbitmq/rabbitmq.conf
EXPOSE 5672 15672