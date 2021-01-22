# dsclient
Project created for bootcamp devSuperior

## Overview
This project was developed as a lesson from bootcamp DevSuperior. The goal of this project was to develop a CRUD of clients.

## Conceptual Model
![](https://github.com/matheeuspc/projectImages/blob/main/conceptual_model.png?raw=true)
## Endpoints Available
  * Get all clients (paged)
  ```java
  [GET] /clients
  ```
  * Get client by id
  ```java
  [GET] /clients/{id}
  ```
  * Create a new client
  ```java
  [POST] /clients
  ```
  * Update a client
  ```java
  [PUT] /clients/{id}
  ```
  * Delete a client
  ```java
  [DELETE] /clients/{id}
  ```
  
  ### Payload to create and update a client
  ```json
  {
  "name": "Person Name",
  "cpf": "12345678901",
  "income": 6500.0,
  "birthDate": "1994-07-20T10:30:00Z",
  "children": 2
}
  ```
