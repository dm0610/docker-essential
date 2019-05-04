FROM debian:latest
MAINTAINER Dmitriy Strelnikov <dm.strelnikov@yandex.ru>
RUN apt-get update && apt-get install -y cowsay fortune
ENTRYPOINT ["/usr/games/cowsay"]
COPY entrypoint.sh /
ENTRYPOINT ["/entrypoint.sh"]
