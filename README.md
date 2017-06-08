# Awesome Cloud Native Java

This is a collection of awesome frameworks for writing Cloud Native Java.

## Backend Service

Frameworks to help you write backend services quickly.

### RESTFul

* [Spring Boot](https://spring.io/guides/gs/rest-service/)
* JAX-RS
  * [Jersey](https://jersey.github.io/) \([example](https://jersey.github.io/documentation/latest/jaxrs-resources.html)\)
  * [Wildfly Swarm](http://wildfly-swarm.io/) \([example](https://github.com/wildfly-swarm/wildfly-swarm-examples/tree/master/jaxrs/jaxrs-cdi)\)
* [Akka HTTP](http://doc.akka.io/docs/akka-http/current/scala/http/) \([example](http://doc.akka.io/docs/akka-http/current/scala/http/routing-dsl/index.html)\)
* [Dropwizard](http://www.dropwizard.io/) \([example](http://www.dropwizard.io/1.1.0/docs/getting-started.html#creating-a-resource-class)\)
* [Spark](http://sparkjava.com/) \([example](http://sparkjava.com/)\)
* [Apollo](https://github.com/spotify/apollo) \([example](https://github.com/spotify/apollo/tree/master/examples/calculator)\)

### RPC

* [gRPC](https://github.com/grpc/grpc-java) \([example](https://github.com/grpc/grpc-java/tree/master/examples/src/main/java/io/grpc/examples/helloworld)\)
* [Avro](http://avro.apache.org/) \([example](https://github.com/phunt/avro-rpc-quickstart)\)
* [Thrift](https://thrift.apache.org/) \([example](https://thrift.apache.org/tutorial/java)\)

## Metrics

Frameworks to expose application metrics:

* [Spring Boot Actuator](https://github.com/spring-projects/spring-boot/tree/master/spring-boot-actuator)

  * [Application Metrics](https://docs.spring.io/spring-boot/docs/current/reference/html/production-ready-metrics.html)

  * Export to Prometheus \([thomasdarimont](https://github.com/thomasdarimont/prometheus-spring-boot-starter), [akaGelo](https://github.com/akaGelo/spring-boot-starter-prometheus), [nickymoeholm](https://github.com/nickymoelholm/prometheus-spring-boot-starter)\)

* [Prometheus](https://github.com/prometheus/client_java) \(lots of examples in the repository\)
  * [JMX Metrics](https://github.com/prometheus/jmx_exporter)
* [Jolokia](https://jolokia.org/)

## Load Balancer

### Server-side / Proxy

* [HAProxy](http://www.haproxy.org/)
* [Linkerd](https://linkerd.io/)
* [Envoy](https://github.com/lyft/envoy)

### Client-side

* [Ribbon](https://github.com/Netflix/ribbon) \([example](https://github.com/Netflix/ribbon/tree/master/ribbon-examples)\)
* [Spring Cloud Netflix](https://github.com/spring-cloud/spring-cloud-netflix) \(uses Ribbon, [example](https://spring.io/guides/gs/client-side-load-balancing/)\)

## API Gateway

* [Zuul](https://github.com/Netflix/zuul) \([example](https://github.com/Netflix/zuul/blob/1.x/zuul-netflix-webapp/src/main/java/com/netflix/zuul/StartServer.java)\)
* [Spring Cloud Netflix](https://cloud.spring.io/spring-cloud-netflix/) \(uses Zuul, [example](https://spring.io/guides/gs/routing-and-filtering/)\)
* Kubernetes Ingress

## Tracing

Frameworks to trace and/or collect trace data:

Server

* [OpenTracing](http://opentracing.io/) / Zipkin

Client

* [Spring Cloud Sleuth](https://cloud.spring.io/spring-cloud-sleuth/)
  * [Spring Cloud Sleuth - Zipkin](https://github.com/spring-cloud/spring-cloud-sleuth/tree/master/spring-cloud-sleuth-zipkin) \([example](https://spring.io/blog/2016/02/15/distributed-tracing-with-spring-cloud-sleuth-and-spring-cloud-zipkin)\)
* [Brave](https://github.com/openzipkin/brave)

## Circuit Breaker & Bulkheads

* [Hystrix](https://github.com/Netflix/Hystrix) \([example](https://github.com/Netflix/Hystrix/tree/master/hystrix-examples/src/main/java/com/netflix/hystrix/examples/basic)\)
* [Spring Cloud Netflix](https://github.com/spring-cloud/spring-cloud-netflix) \(uses Hystrix, [example](https://spring.io/guides/gs/circuit-breaker/)\)
* [resillence4j](https://github.com/resilience4j/resilience4j) \([example](https://github.com/resilience4j/resilience4j#circuitbreaker-retry-and-fallback)\)
* [Akka Circuit Breaker](http://doc.akka.io/docs/akka/current/scala/common/circuitbreaker.html) \([example](http://doc.akka.io/docs/akka/current/scala/common/circuitbreaker.html#java)\)

## Service Registry

* [Eureka](https://github.com/Netflix/eureka)
* [Spring Cloud Netflix](https://github.com/spring-cloud/spring-cloud-netflix) \(uses Eureka, [example](https://spring.io/guides/gs/service-registration-and-discovery/)\)
* [Zookeeper](https://zookeeper.apache.org/)
* [Consul](https://www.consul.io/)

## Application Generators

* [JHipster](https://jhipster.github.io/) \([example](https://jhipster.github.io/microservices-architecture/)\)

## Container Orchestration

* [Kubernetes](https://www.gitbook.com/book/saturnism/cloud-native-java-awesome/edit#)

* [Docker Swarm](https://docs.docker.com/engine/swarm/)

* [Mesosphere](https://dcos.io/)

## Platform as a Service

* [OpenShift](https://www.openshift.org/)
* [Cloud Foundry](https://www.cloudfoundry.org/)

## Service Mesh

* [Istio](https://istio.io/)



