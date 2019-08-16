FROM node:10.16.0-jessie
RUN apt-get update \
  && apt-get install -y postgresql postgresql-contrib \
  && apt-get install sudo \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
