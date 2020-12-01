FROM openjdk:8u252-jre-slim

WORKDIR /app/
ADD /var/assembling/workspace/hwstaff_zhoutong/servicecomb-samples/java-chassis-samples/springmvc-sample/springmvc-provider/target/springmvc-provider-2.1.2.jar /app.jar

EXPOSE 8080
ENTRYPOINT ["/usr/local/openjdk-8/bin/java", "-jar", "/app.jar"]
