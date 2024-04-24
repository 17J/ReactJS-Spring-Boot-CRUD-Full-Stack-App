FROM openjdk
EXPOSE 8082
ADD target/springboot.war springboot.war
ENTRYPOINT ["java","-jar","/springboot.war"]
