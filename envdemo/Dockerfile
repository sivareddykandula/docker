FROM openjdk:8
LABEL author="sivareddyk"
LABEL organization="Kcompany"
ENV applicationpath='/springpeticlinic.jar'
ENV dummy='dummy'
ARG doownloadlocation
ADD ${doownloadlocation} ${applicationpath}
EXPOSE 8080
CMD [ "java", "-jar", ${applicationpath} ]