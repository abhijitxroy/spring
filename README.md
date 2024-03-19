# spring

    Spring Bean Lifecycle
    
    Difference between Spring context close() & registerShutDownHook()
    
    How many ways spring lifecycle can be achieved? -> 3
    
    Spring lifecycle demo with database
    
    How to handle Custom exception in spring boot
    
    What is Field Injection?
    
    When Spring Bean get Destroyed?
    
    Outer Bean prototype & Inner Bean Singleton, What if we called it twice?
    
    Explain about @Configuration, @Autowire, @Qualifier
    
    5 Spring Excpetion
    
    5 spring Annotations Excluding sterotype annotation
    
    @Component vs @Bean . What is the difference between creating a bean with @Bean and creating a bean with @Component?
    
    What is a BeanFactoryPostProcessor?
    
    Bean Factory Post Processor Code walkthrough
    
    Who is reposible for create proxy?
    
    application.properties vs application.yaml , Which will load first ?
    
    What if we don't have the spring MVC available in the class path? Will it be created any application context?
    
    Explain the need of a global exception handler in spring boot ?
    
    @component vs @service vs @repository
    
    What will happen if you will use @service over a DAO?
    
    how you will call the @Predestory marked methods in the standalone application.
    
    Explain the helper class that initializes and destroys the web application context
    
    How to create custom validators in spring?
    
    What is the Difference between Exception Handler & Fallback method
    
    Factory Pattern in Spring? -> BeanFactory
    
    How to read application.properties data in spring? How many ways are there? -> env.getProperty(key) or @Value("${key}) or normal java code (Properties.getProperties(key))
    
    What will happen while injecting prototype bean into a singleton bean (AKA Scope bean injection problem)-> using Scoped Proxy or lookup method injectionor ApplicationContextAware or Objectfactory
    
    What is Qualifier and why we need this?

# Spring Boot

    What is Spring Boot Auto-configuration? Why do we need Spring Boot Auto Configuration?
    
    How Spring boot internally works (Explain the run() method in Spring boot)?
    
    Why do we need a spring-boot-maven plugin?
    
    Explain @SpringBootApplication = @EnableAutoConfiguration + @Configuration + @ComponentScan
    
    What are Spring boot starters and name a few important Spring boot starter dependencies?
    
    How does Spring Enable Creating Production-Ready Applications in Quick Time?
    
    What are Profiles in Spring Boot? How do you use it?
    
    Explain the use of Springboot starter parent
    
    How the dispatcher servlet is set up in a spring boot project?
    
    how the dispatcher servlet in spring boot gets auto-configured?
    
    How to Remove Cyclic Dependency from Spring Boot
    
    How Spring-boot application will know that input is in the form of XML or JSON payload?
    
    How to Use Jetty Instead of Tomcat in Spring-Boot-Starter-Web?

# Spring Cloud

    Spring Load balancer Vs Ribbon
    Default load balancing mechanism -> round robbin or sequentially
    Client Side Load balancing -> Spring Cloud Netflix Eureka
    What is the role of Discovery Service -> discovering service info not load balancing
    Server Side Load balancing -> AWS load balancer
    Spring Fault Tolarance
    How Cricuit Breaker Works?
    What are the design pattern you have used in Microservices
    How Inter communication can be implemented in microservices
    Microservice architecture
    Explain what issue Service discovery solve
    How would you implement SSO for Microservice Architecture
    Diff bet SOA & Microservices
    Which pattern your project follow in microservice?
    What are the RestClients you have used in your project?-> blocking - RestTemplate, NonBlocking-> Webclient, FeignClient(OpenFeign)
    Pros & Cons of RestTemplate over FeignClient
    RestTemplate difference between getForEntity() & getForObject()
    How to create a RestTemplate to consume an external API?
    Should you use JWT or Session-based authentication in the microservices environment?
    Are you using API gateway in your project?
    What is bounded context in Microservice
    Lets you have 10 microservices & 5th services impacted . how will you know from logging which got impacted? centralized or individual?
    When we have mutiple microservice and when we jump from one to another, how the other miscroservice maintain user session? -> token to authenticate, localStorage
    There is a huge load on microservie server & multiple logs are generated (1lac user ) for all logs will be generated and maintained all sessions for all users. 
    how will you identify this log is for a particular user? -> Event sourcing
    How do you maintain microservice scalablity? -> docker, Kubernate
    What is API Gateway? What problem it resoleve? -> Dynamic Routing, Loadblanacing, Security, rate limiting, monitoring
    What problem Spring Cloud server config solve m/s?
    What problem Distributed Tracing Pattern solve in m/s? -> Spring Cloud Sleuth and Spring Cloud Zipkin
    What problem Circuit Breaker solve m/s?-> fault tolarance, fallback method, retry, rate limit, circuit break
    How to check microservice performance. -> Latency(how fast), Throughput(how many) -> micrometer-> promotheus+grafana & aws cloud watch
    What are the Functional & technical challenges in microservices
    How do you push data in config server at runtime=> using spring actuator /actuator/refresh or using spring cloud bus /actuator/bus-refresh or /monitor endPoint

# Spring Security

What is ThreadLocal in Java? Memory available to all threads, Give a real time scenario -> Sprincg Security authenctication
Spring SecurityContext scope (Security life cycle in Spring Security)
How does Basic Authentication work in Rest API?
Code walkthrough on the spring security internal workflow

Basic Auth

JSON Web Token - JWT

    How JWT work? Internal fow of JWT
    
    How to craete a token by JWT?
    
    How JWT token validated?
    
    How long jwt token valid & after that what will happen(refresh a new token or expire)?
    
    JWT token default expiry time?

OAuth 2.0

