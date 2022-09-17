
# Springboot Microservices

Spring microservices demo project which includes cloud config server, service registry, two sample microservice projects, api gateway, hystrix dashboard with zipking & sleuth tracing.

More about microservices on: https://www.kodingexpert.com/microservices-with-springboot/

Cloud config repo on: https://github.com/gothamaha/config-server-spring-boot-apps



## Projects Included

| Service       | Scope                                                                |
| ----------------- | ------------------------------------------------------------------ |
| config-server-spring-boot-apps | Configurations on Github |
| cloud-config-server | Configuration Server serving the configs from Github|
| service-registry | Eureka service registry to resolve running services access |
| department-service| Sample microservice using a Department |
| user-service | Sample microservice using a Users for Deparment |
| cloud-gateway | API Gateway for handling requests acting as a proxy, integrated with Hystrix |
| hystrix-dashboard | Hystrix dashboard for monitoring the status of requests |
| zipkin.jar | Tracing logs and errors of microservice and health status |

