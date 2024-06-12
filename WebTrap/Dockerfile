FROM debian:latest

WORKDIR /WebTrap/
ADD . /WebTrap

RUN apt update && \
    apt full-upgrade -y && \
    apt install -y curl unzip wget && \
    apt install --no-install-recommends -y php && \
    apt clean
CMD ["./WebTrap.sh"]
