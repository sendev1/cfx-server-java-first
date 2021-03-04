To capture CXF config -Dspring.profiles.active=capture

Remote debug java -agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=*:5005 -jar build/libs/cxf-server-java-first-0.0.1-SNAPSHOT.jar