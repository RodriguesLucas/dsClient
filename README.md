# Ds Client
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/RodriguesLucas/dsClient/blob/main/LICENSE) 

DsClient é uma aplicação Backend, desenvolvida para avaliação no decorrer de um Bootcamp Spring, curso realizado pela [DevSuperior](https://learn.devsuperior.com/).

A aplicação consiste em um microserviço onde é possível criar, alterar, visualizar e excluir um determinado cliente, além de visualizar a lista de clientes cadastrados.

![Modelo Conceitual](https://github.com/RodriguesLucas/dsClient/blob/main/ASSETS/ModeloConceitual.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- Jpa / Hibernate
- Maven

# Como executar o projeto
## Back end
Pré-requisito: Java 11

```bash
# Clonar o repositório
git clone https://github.com/RodriguesLucas/dsmovie.git

# Entrar na pasta do projeto back end
cd backend

# Executar o projeto
./mvnw spring-boot:run

```
```bash
# Sugestão: Usar o Postman para testar as requisições
  URL padrão da requisição: http://localhost:8080/products
  
  Get: http://localhost:8080/clients/{id}
  
  Get: http://localhost:8080/clients?page={numberPage}&linesPerPage={linesPerPage}&orderBy={orderBy}&direction={direction}
  
  Post: http://localhost:8080/clients
  
  Put: http://localhost:8080/clients/{id}
  
  Delete: http://localhost:8080/clients/{id}
```
# Autor
Lucas Rodrigues

https://www.linkedin.com/in/lucas-rodrigues-0558a3205/
