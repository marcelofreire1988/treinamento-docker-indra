FROM debian
LABEL app="Indra"
ENV TREINAMENTO="DOCKER"
RUN apt-get update && apt-get install -y stress

CMD stress --cpu 1 --vm-bytes 64M --vm 1
