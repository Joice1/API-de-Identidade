# 🔐 API de Autenticação  

## 📌 Descrição  
Esta API foi desenvolvida em **Java com Spring Boot** para realizar o **processo de autenticação e controle de acesso de usuários**.  
O projeto implementa boas práticas de segurança, documentação e testes automatizados, garantindo robustez e escalabilidade.  

---

## 🛠️ Tecnologias utilizadas  
- **Spring Boot** → estrutura principal da aplicação.  
- **Spring Data JPA** → integração com banco de dados relacional.  
- **JWT (JSON Web Tokens)** → autenticação baseada em tokens.  
- **Docker & Docker Compose** → virtualização e gerenciamento de containers.  
- **Jakarta Validation** → validação de dados de entrada.  
- **Swagger** → documentação interativa da API.  
- **PostgreSQL** → banco de dados utilizado.  
- **JUnit** → testes unitários.  

---

## ⚙️ Funcionalidades  
- Cadastro de usuários com validação de dados.  
- Autenticação via **JWT**.  
- Geração e renovação de tokens.  
- Rotas seguras e protegidas.  
- Documentação interativa disponível via **Swagger UI**.  

---

## 🚀 Como executar o projeto  

### Pré-requisitos  
- [Java 17+](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)  
- [Maven](https://maven.apache.org/)  
- [Docker](https://www.docker.com/)  

### Passos  
# 1. Clonar o repositório

git clone: 
```bash
https://github.com/seu-usuario/seu-repositorio.git
```


## 🖥️ Aplicação disponível

A aplicação estará disponível em:  
```bash
[http://localhost:8082](http://localhost:8082)
```

---

## 📖 Documentação

Após rodar a aplicação, acesse o Swagger UI:  
```bash
[http://localhost:8082/swagger-ui.html](http://localhost:8082/swagger-ui.html)
```

---

## 🧪 Testes

Os testes foram implementados com **JUnit**. Para executá-los:  
```bash
mvn test
```

### 🗂️ Estrutura do projeto (resumida)

```text
src/main/java
 └── com.exemplo.api
      ├── configurations
      ├── controllers
      ├── dtos
      ├── entities
      ├── exceptions
      ├── handlers
      ├── helpers
      ├── repositories
      └── services
```

# 🐳 Subir os containers (API + PostgreSQL)
```bash
docker-compose up -d --build
```
