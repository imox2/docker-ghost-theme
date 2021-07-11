FROM ghost:4.8.4
RUN apt-get update -y && \
    apt-get install -y default-mysql-client
COPY ./wait-for-it.sh /usr/local/bin/wait-for-it.sh
