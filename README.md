# 📇 Agenda de Contatos de Funcionários

Este projeto consiste em uma **aplicação web para gerenciamento de contatos de funcionários/clientes**, permitindo cadastrar, listar, editar e remover informações de forma organizada e eficiente.

O sistema foi desenvolvido utilizando **Java no backend**, com arquitetura baseada em **DAO (Data Access Object)** e **Servlets**, além de um **frontend simples e funcional em HTML, CSS e JavaScript**, realizando comunicação com o servidor via requisições HTTP.


## 🚀 Funcionalidades

- Cadastro de clientes/funcionários
- Cadastro de contatos vinculados aos clientes
- Listagem de contatos
- Edição de informações
- Exclusão de registros
- Integração entre frontend e backend
- Organização em camadas (Model, DAO, Servlet)

## 🛠️ Tecnologias Utilizadas

### Backend
- Java
- Servlets
- JDBC
- Maven
- MySQL
- Padrão DAO
- Filtro CORS
- Conexão via `ConnectionFactory`

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla JS)

## 🗂️ Estrutura do Projeto

agendaContatos-main
│
├── backend
│ ├── src/main/java
│ │ ├── dao
│ │ ├── model
│ │ ├── servlet
│ │ └── util
│ └── agenda.sql
│
└── frontend
├── Agenda de Contatos de Clientes.html
├── style.css
└── script.js

## 🗄️ Banco de Dados

O script SQL para criação das tabelas está disponível no arquivo:

backend/agenda.sql

## ▶️ Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/JeanAmaral181/Contato-de-Funcionario.git
Configure o banco de dados MySQL utilizando o arquivo agenda.sql.

Ajuste as credenciais do banco na classe:

Copiar código
ConnectionFactory.java
Execute o backend em um servidor como Apache Tomcat.

Abra o arquivo HTML do frontend no navegador:

Copiar código
frontend/Agenda de Contatos de Clientes.html
