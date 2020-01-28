FROM node:lts-buster
RUN wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | apt-key add - \
  && echo "deb http://repo.mongodb.org/apt/debian buster/mongodb-org/4.2 main" | tee /etc/apt/sources.list.d/mongodb-org-4.2.list \
  && apt-get update \
  && apt-get install -y sudo mongodb-org \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
RUN mkdir -p /data/db
