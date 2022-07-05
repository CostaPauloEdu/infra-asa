#Download latest image of Ubuntu
FROM ubuntu:latest

#Author
LABEL maintener="Paulo Eduardo Azevedo da Costa"

#Update and install bind9 (and others components)
RUN apt-get update \
  && apt-get install -y \
  bind9 \
  bind9utils \
  bind9-doc \
  nano \
  dnsutils \
  iputils-ping \
  procps


# Start bind9 service
CMD /usr/sbin/named ; tail -F /dev/null