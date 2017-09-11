FROM java:8u66-jdk

MAINTAINER kevin kevin.wu@magicwindow.cn

ADD target/gs-rest-service-0.1.0.jar /opt/gs-rest-service-0.1.0.jar

EXPOSE 8080

CMD java -Dserver.port=10501 -Dmanagement.security.enabled=false -Djava.security.egd=file:/dev/./urandom -jar
/opt/gs-rest-service-0.1.0.jar
