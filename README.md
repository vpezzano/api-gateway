# api-gateway
This microservice works in conjunction with two other microservices, employee-service and spring-eureka-server.
The Hystrix dashboard view is reachable at: http://localhost:8010/hystrix. The url to monitor in the dashboard is: 
http://localhost:8010/actuator/hystrix.stream.
It's built starting from here:
https://howtodoinjava.com/spring-cloud/microservices-monitoring