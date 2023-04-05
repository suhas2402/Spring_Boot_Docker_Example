FROM openjdk:17
EXPOSE 8098
ADD target/sb-k8s.jar sb-k8s.jar
ENTRYPOINT ["java","-jar","/sb-k8s.jar"]