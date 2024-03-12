# Microservices-Template-Golang
Prerequisites:
1. Golang compiler
2. JDK
3. VSCode
4. Eclipse
5. Docker


To run the Golang API's :
1. Clone the repository.
2. Open the repo and navigate to the ` Golang API ` folder.
3. Give the command `docker-compose up ` to run the container 

To run the Service Discovery Server:
1. Navigate to the path `Service Discovery and API Gateway\discovery-service\src\main\java\pl\piomin\microservices\advanced\discovery `
   and run ` Application.java ` as a Spring Boot Application.
   

To run the API Gateway:
1. Navigate to the path `Service Discovery and API Gateway\gateway-service\src\main\java\pl\piomin\microservices\advanced\gateway `
   and run ` Application.java ` as a Spring Boot Application.   
 
 
Ports of Different Application :
- 8080 : Golang API's
- 8761 : Service Discovery Server
- 8765 : API Gateway
- 9090: Prometheus 
- 3000: Grafana
