FROM ubuntu:18.04
LABEL author="sivareddyk"
LABEL organization="Kcompany"
RUN apt-get update && apt-get install apache2 -y
EXPOSE 80
CMD [ "apache2ctl", "-D", "FOREGROUND" ]