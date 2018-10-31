# Getting Started with Docker Compose for Selenium Grid

 This is a step-by-step introduction to use the Selenium Docker images using a hub/node configuration and docker-compose to execute the tests.

##### To Run the Grid use the below command
```
docker-compose up -d
```

##### Scaling the grid on-demand
```
docker-compose scale <service-name>=<no.of nodes>

Example:
docker-compose scale selenium-chrome=5
```
