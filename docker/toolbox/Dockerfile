  
FROM alpine
RUN apt-get -y update
RUN apt-get -y install nmap apache2
EXPOSE 80
CMD apache2ctl -D FOREGROUND
