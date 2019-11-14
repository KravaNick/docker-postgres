FROM postgres:11-alpine
RUN unlink /docker-entrypoint.sh
COPY docker-entrypoint.sh /usr/local/bin
RUN ln -s /usr/local/bin/docker-entrypoint.sh /