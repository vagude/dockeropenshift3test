FROM java:8
EXPOSE 8080
ADD ["/dockeropenshift3test-0.1.0.jar", "/usr/src/app/demo.jar"]
RUN chmod +x "/usr/src/app/demo.jar"
#ENTRYPOINT ["java","-jar","/usr/src/app/demo.jar"]
ENTRYPOINT exec java -Xmx512g -Xms1g -jar /usr/src/app/demo.jar