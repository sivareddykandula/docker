FROM ubuntu:latest
LABEL authour="sivareddyk"
LABEL organization="Kcompany"
RUN apt-get update && apt-get install apache2 -y
WORKDIR /var/www/html/
COPY index.html .
CMD [ "echo", "hellosiva" ]
