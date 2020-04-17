FROM registry.redhat.io/openjdk/openjdk-11-rhel8

ADD kafdrop.sh /
ADD kafdrop*/ /

WORKDIR /

RUN chmod +x /kafdrop.sh

ENTRYPOINT ["/kafdrop.sh"]
