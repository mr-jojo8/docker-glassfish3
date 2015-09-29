This repo extend tutum team.


docker build -t duruu/glassfish3 .

docker run -d -p 4848:4848 -p 8080:8080 -p 8181:8181 duruu/glassfish3

docker logs <CONTAINER_ID>

docker run -d -p 4848:4848 -p 8080:8080 -p 8181:8181 -e GLASSFISH_PASS="mypass" duruu/glassfish3