# Test Spring Cloud Server Multiple Files
docker run -it -p 8888:8888 -e JAVA_OPTS='-Dspring.cloud.config.server.git.uri=https://gitlab.kudelski.com/bouscass/test-spring-cloud-server-multiple-files -Dspring.cloud.config.server.git.search.paths="config/*"'  hyness/spring-cloud-config-server
