# EcoRide Config Server

This repository hosts the **centralized configuration** for all EcoRide microservices. It is built using **Spring Cloud Config Server**.

## Project Structure

| Folder / File       | Description |
|--------------------|-------------|
| ecoride-api-gateway | API Gateway configs |
| ecoride-user-service | User Service configs |
| ecoride-driver-service | Driver Service configs |
| ecoride-ride-service | Ride Service configs |
| ecoride-auth-service | Auth Service configs |
| common/application.properties | Shared configs for all microservices |

> Each service folder contains its own `application.properties`.  
> The `common/application.properties` file contains shared configurations used across services.
