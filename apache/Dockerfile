FROM ubuntu"latest
LABEL author="sivareddyk"
LABEL organization="Kcompany"
RUN apt-get update && apt-get install apache2 -y
USER www-data
CMD [ "whoami" ]