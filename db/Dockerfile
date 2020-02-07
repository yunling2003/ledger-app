FROM mongo:3.6

RUN mkdir -p /data/db

VOLUME /data/db

EXPOSE 27017

ENTRYPOINT ["usr/bin/mongod", "--bind_ip_all"]