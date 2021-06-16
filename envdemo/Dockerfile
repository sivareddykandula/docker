FROM openjdk:8
LABEL author="sivareddyk"
LABEL organization="Kcompany"
ENV applicationpath='/springpeticlinic.jar'
ENV dummy='dummy'
ENV workingdirectory='/spc'
ARG downloadlocation='https://referenceappkhaja.s3-us-west-2.amazonaws.com/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar'
RUN mkdir ${workingdirectory}
WORKDIR ${workingdirectory}
ADD ${doownloadlocation} "${workingdirectory}/${applicationpath}"
EXPOSE 8080
CMD [ "java", "-jar", "${workingdirectory}/${applicationpath}" ]