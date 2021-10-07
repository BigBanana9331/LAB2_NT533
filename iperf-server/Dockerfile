FROM ubuntu

RUN apt-get update
RUN apt-get install -y iperf

ENTRYPOINT ["iperf","-s","-u"]