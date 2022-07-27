---

mindmap-plugin: basic

---

# Springboot

## JAVA

## Servlet ^158df242-d983-a980
- What is Servlet
- Life Cycle Method
   - public init()
   - getServletConfig()
   - Service(request , response)
   - getServletInfo()
   - void destory()
- 3 way to create Servlet Application
   - 1. Implementation of Interface
   - 2. Abstract Generic Servlet Class
   - 3. HttpServlet Class
- RequestDispaycher
   - Forward()
   - Include()
   - Redirect()
- Internal Working of Servlet
- Deployment Descriptor
- Parameters , Attributes
- Session Tracking
   - Cookies
   - Hidden form
   - URL Rewritting
   - Http Session
- Filters
   - Filter
      - init()
      - dofilter()
      - destory()
   - FilterChain
   - FilterConfig

## JSP ^adad71a3-38cf-44a1
- JSP why?
- Important Tags of JSP
   - Declaration Tag
   - Scriplet Tag
   - Expression Tag
   - Jsp Directive Tag
      - Page Directive Tag
      - Include Directive Tag
      - Tag Lib Directive Tag
   - Error Handling
   - JSP Implicit Object

## Spring ^d2e3a695-eede-287f
- SpringCore
   - Bean Life Cycle
   - Dependency Injection
   - Inversion of Control
   - Bean Factor and Application Context
   - Expression Language
   - AOP
- Databases
   - Relational Database
      - SQL Server
      - Postgre SQL
      - MariaDB
      - MYSQL
   - NOSQL
      - MongoDB
      - Redis DB
      - CouchDB
   - CloudDB
      - DynamoDB
      - CosmosDB
- ORM's
   - Hibernate
   - OpenJPA
   - TopLink
   - Eclipse Link
- Caching
   - Type of Cache
      - CDN Caching
      - WebServer Caching
      - Database Caching
      - InMemory Caching
   - @Annotation ^5660e421-bfc9-2955
      - @EnableCaching
      - @Cacheable
      - @Cacheput
      - @CacheEvict
      - @Caching
   - RegisterCache Engine
      - Jcache
      - EhCache
      - Hazelcast
      - Couchbase
      - Redis
      - Caffeine
      - SimpleCache
      - Cache2K
- Testing ^d07c2bb2-1ce6-8419
   - Unit Behavior, Integration, Load Testing
      - Junit
      - Mockito
      - Tsung
      - MockServer
   - E2E Testing
      - Selenium
- Logging ^d9f60552-4b25-dc4a
   - Logback
   - Log4J2
   - TinyLog
   - SLF4J
- Spring Security ^757e7fbc-4b4b-6bf8
   - Authentication
   - Authorization (rolebase)
   - Basic Auth (base64 Encoding)
   - Bearer Token
   - JWT (Json Web Token)
   - OAuth 1.0 / OAuth 2.0
   - Amazon WebService Signature
- Deploying

## Design Pattern's ^7157e523-f608-1e83
- SOLID Principle
- UML (class Diagram)
- SIngleton Design Pattern
- Decorator Design Pattern
- Strategy Design Pattern
- Adapter Design Pattern
- Command Design Pattern
- Iterator Design Pattern
- Curiously recurring TemplateDesign Pattern
- Flyweight Design Pattern
- Facade Design Pattern
- Proxy Design Pattern
- Composite Design Pattern
- prototype Design Pattern
- Abstract Design Pattern
- Bridge Design Pattern
- Chain

## General Skills ^190b631f-4107-02db
- GIT , GITHUB
- HTTP(S) Protocol
   - Method ^802cd859-6b18-3276
      - GET
      - POST
      - PUT
      - PATCH
      - DELET
      - OPTIONS
   - Status
      - Information 1XX
      - Successfull 2XX
      - Redirection 3XX
      - Client Error 4XX
      - Server Error 5XX
- POSTMAN, ThunderClient, Insomnia

## JDBC ^b784e741-8382-f32d
- 1. load class / driver
   - 1.1 classForName("com.---")
   - 1.2 DriverManager.register.Driver()
- 2. Connection Creation
- 3. Create Query
- 4. Process the Query/Data
- 5. Close the Connection