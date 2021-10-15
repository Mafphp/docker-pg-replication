FROM postgres:10
COPY ./docker-entrypoint.sh /docker-entrypoint-initdb.d/docker-entrypoint.sh
RUN apt update && apt install iputils-ping -y
