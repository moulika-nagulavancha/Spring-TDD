# Spring-TDD
An E-Commerce project in Spring using the Test Driven Development (TDD) approach

# Spring boot support for Unit testing
- SpringBootTest : Loads the Spring Application context into tests
- MockMvc : Comprehensive testing for Spring controllers
- MockBean : Mockito Integration

# Third party extensions for Back-end resources
- DBUnit : Prepopulate & clean up database between tests
- MongoDB : Custom extension to manage MongoDB
- WireMock : Simulate third-party API responses

# Architecture
Typical Microservice:

    [Controller ----> Service ----> Repository] ----> [Database]

# Integration Testing
![img.png](images/integration-testing.png)

# Testing the Controller
![img.png](images/controller-testing.png)

- Role of a Controller
![img.png](images/role-of-controller.png)

- MockMvc features
![img.png](images/mock-mvc-features.png)
![img.png](images/mock-mvc-demo.png)

# Testing the Service
![img.png](images/service-testing.png)
- Role of a Service
![img.png](images/service-role.png)

# Testing the Repository
![img.png](images/repository-testing.png)
- Strategies
![img.png](images/repository-strategies.png)
- DBUnit & DBUnitExtension
![img.png](images/DBUnit.png)
- Mock Database creation using YAML
![img.png](images/mock-h2-db-yaml.png)