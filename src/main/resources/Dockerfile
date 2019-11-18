FROM java:8
VOLUME /tmp

ADD /home/vsts/work/1/a/target/devops.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
