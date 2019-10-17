FROM node:lts-buster
RUN apt-get update \
  && apt-get install -y postgresql postgresql-contrib sudo \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
