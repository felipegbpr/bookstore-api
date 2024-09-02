# 🕮 BookStore API
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/felipegbpr/springboot-bookstore-api/blob/main/LICENSE)

## 📃 Sobre o projeto 

https://springboot-bookstore-api-2mvy.onrender.com

Este projeto é uma aplicação Web API feita com Java e Springboot. O objetivo desse projeto consiste no fornecimento de um serviço online para cadastro de livros e suas categorias, 
suas funcionalidades são baseadas no modelo **CRUD** que representa uma série de operações performadas no modelo estrutural de aplicações. 

## 💻 Tecnologias utilizadas
![Static Badge](https://img.shields.io/badge/JAVA-lang?style=for-the-badge&logo=java&logoSize=amg&color=black)
![Static Badge](https://img.shields.io/badge/Spring_Boot-framework?style=for-the-badge&logo=spring&logoSize=amg&color=black) 
![Static Badge](https://img.shields.io/badge/Maven-lib?style=for-the-badge&logo=maven&logoSize=amg&color=black)
![Static Badge](https://img.shields.io/badge/MySQL-database?style=for-the-badge&logo=mysql&logoSize=amg&color=black)
![Static Badge](https://img.shields.io/badge/H2_DATABASE-database?style=for-the-badge&logo=h2database&logoSize=amg&color=black)
![Static Badge](https://img.shields.io/badge/JPA_%2F_HIBERNATE-ORM?style=for-the-badge&logo=hibernate&logoColor=yellow&color=black)





## 🔍 Explore a API
### Livros
| Method  | URL   | Description |
|---|---|---|
| GET  | /livros/all  |  Obtém todos os livros cadastrados |   |   |
| GET |  /livros/{id} |  Obtém livro por id |   |   |
| POST  |  /livros?categoria={id} |  Cria um novo livro associado a uma categoria |   |   |
| PUT  |  /livros/{id} |  Atualiza os dados de um livro previamente cadastrado |   |   |
| DELETE | /livros/{id} | Deleta um livro que já esteja cadastrado | | |

### Categorias
| Method  | URL   | Description |
|---|---|---|
| GET  | /categorias  |  Obtém todas as categorias cadastradas |   |   |
| GET |  /categorias/{id} |  Obtém uma categoria por id |   |   |
| POST  |  /categorias |  Cria uma nova categoria |   |   |
| PUT  |  /categorias/{id} |  Atualiza os dados de uma categoria previamente cadastrada |   |   |
| DELETE | /categorias/{id} | Deleta uma categoria que já esteja cadastrada | | |

## 🌐 Implantação em produção
- Render

## ⚙️ Como executar
🚩 Pré-requisitos: JAVA 17 & MAVEN

1. clonar repositório
```bash
git clone git@github.com:felipegbpr/springboot-bookstore-api.git      
```
2. executar o projeto
```bash
./mvnw spring-boot:run   
```
   
## 👔 Autor

Felipe Borges

Perfil no LinkedIn: https://www.linkedin.com/in/felipe-gsb/
