Docker Glassfish-3.1.2
==================================

Usage
------
	
	docker build -t duruu/glassfish3 .

	docker run -d -p 4848:4848 -p 8080:8080 -p 8181:8181 duruu/glassfish3

	docker logs <CONTAINER_ID>

	docker run -d -p 4848:4848 -p 8080:8080 -p 8181:8181 -e GLASSFISH_PASS="password" --name glassfish3 duruu/glassfish3

Memory limit /this case : 2GB/

	docker run -d -m 2GB-p 4848:4848 -p 8080:8080 -p 8181:8181 -e GLASSFISH_PASS="password" --name glassfish3 duruu/glassfish3