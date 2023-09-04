# Spring Web API

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:837/1*MWaFPsFv41TlfUpUkIuHcw.png">
</p>

---

## Descrição

Este projeto é uma API Web desenvolvida usando o framework Spring Boot para gerenciar operações relacionadas a usuários. Ele oferece funcionalidades de autenticação e autorização com JWT (JSON Web Tokens) para garantir a segurança dos endpoints. A API também utiliza um banco de dados H2 para armazenar os dados dos usuários.

---

## Funcionalidades Principais

- **Cadastro de Usuários**: A API permite a criação de novos registros de usuários no sistema.

- **Autenticação e Geração de Tokens**: Os usuários podem fazer login e obter tokens JWT para acessar endpoints protegidos.

- **Listagem de Usuários**: Você pode listar todos os usuários cadastrados na API.

- **Exclusão de Usuários**: A API oferece a funcionalidade de exclusão de usuários com base em seus IDs.

---

## Configuração

Para executar esta API em sua máquina local, siga estas etapas:

1. Clone o repositório para o seu ambiente local.
2. Configure as propriedades de conexão com o banco de dados H2 no arquivo `application.properties`.
3. Execute a aplicação Spring Boot usando a IDE de sua escolha ou o comando `./mvnw spring-boot:run`.
4. Acesse a API em `http://localhost:8080`.

---

## Autenticação JWT

A API utiliza JWT para autenticação e autorização. Você pode configurar as propriedades relacionadas a JWT no arquivo `application.properties`. Certifique-se de definir a chave secreta (`security.config.key`) e o prefixo do token (`security.config.prefix`) de acordo com suas preferências.

---

