FROM postgres:10-alpine
COPY docker-entrypoint.sh /usr/local/bin
RUN unlink /docker-entrypoint.sh \
  && chmod 777 /usr/local/bin/docker-entrypoint.sh \
  && ln -s /usr/local/bin/docker-entrypoint.sh /