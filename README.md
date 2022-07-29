# Eureka Discovery-server
Eureka Discovery server for my microservices project handles microservices registry. 

## Case
Microservices E-commerce project consists of several microservices. Together they build an e-commerce distributed software system which includes:

## Backend
😃 User service -  see the repository [here](https://github.com/JordanRad/s3-account-service)

📦 Order service  -  see the repository [here](https://github.com/JordanRad/s3-order-service)

🏬 Product service -  see the repository [here](https://github.com/JordanRad/s3-product-service)

🌐 Discovery server -  see the repository [here](https://github.com/JordanRad/s3-discovery-server)

🔀 Gateway -  see the repository [here](https://github.com/JordanRad/s3-proxy)

## Frontend

🖥️ Customer application - see the repository [here](https://github.com/JordanRad/s3-microservices-client)

🖥️ Admin application -see the repository [here](https://github.com/JordanRad/s3-microservices-client)

## My discovery server includes:
- Zuul Gateway on port: **8080**
- Account service on port: **8081**
- Order service on port: **8082**
- Product service on port: **8083**

## Architecture
<img height ="800" src="https://github.com/JordanRad/s3-microservices-client/blob/master/documentation/ProjectDiagram.png">
