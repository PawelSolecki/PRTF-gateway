

# API Gateway 

## Service Overview
API Gateway is the single entry point to all backend services. It handles request routing, filtering, basic authorization, and monitoring. Built with Spring Cloud Gateway, it supports declarative route definitions, custom filters, CORS handling, and seamless integration with security and monitoring tools.

## Main README

For the overall project description and demo instructions, see the main README [here](https://github.com/PawelSolecki/PRTF#).

## Tech Stack
![Java 17](https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud Gateway](https://img.shields.io/badge/Spring_Cloud_Gateway-6DB33F?style=flat-square&logo=spring&logoColor=white)

## Setup & Configuration

### 1. Run with Docker Compose (recommended)
1.	Make sure you have Docker and Docker Compose installed.
2.	From the project root, run:
```shell
docker compose up --build
   ```
3.	The service will be available at:
      http://localhost:8090

      


