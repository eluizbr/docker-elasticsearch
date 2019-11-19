FROM rabbitmq:3.8.1-management-alpine
# RUN rabbitmq-plugins enable --offline rabbitmq_mqtt rabbitmq_federation_management rabbitmq_stomp
# ADD ./docker/rabbitmq/rabbitmq.conf /etc/rabbitmq/
# ADD ./docker/rabbitmq/definitions.json /etc/rabbitmq/
# RUN chown rabbitmq:rabbitmq /etc/rabbitmq/rabbitmq.conf /etc/rabbitmq/definitions.json
# RUN rabbitmqctl add_user admin vp62018
# ADD init.sh /init.sh
# RUN chmod +x /init.sh
EXPOSE 5672 15672
# CMD [ "/init.sh" ]