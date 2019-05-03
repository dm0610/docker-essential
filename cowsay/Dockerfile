FROM debian:latest
RUN apt-get update && apt-get install -y cowsay fortune
ENTRYPOINT ["/usr/games/cowsay"]
COPY /home/vagrant/docker-essential/cowsay/entrypoint.sh /
ENTRYPOINT ["/entrtypoint.sh"]
