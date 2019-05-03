FROM debian:latest
RUN apt-get update && apt-get install -y cowsay fortune
ENTRYPOINT ["/usr/games/cowsay"]
COPY entrypoint.sh /
ENTRYPOINT ["/entrtypoint.sh"]
