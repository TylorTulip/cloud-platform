FROM java:8-jre
MAINTAINER Edison Feng <edison.feng@fulaan.com>

ADD ./target/monitoring-center.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/monitoring-center.jar"]

EXPOSE 8989