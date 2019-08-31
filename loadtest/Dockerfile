FROM quay.io/loderosier/locustgrpc
ADD locust /loadtests
WORKDIR /loadtests
RUN chmod 755 ./run.sh
ENTRYPOINT ["./run.sh"]
