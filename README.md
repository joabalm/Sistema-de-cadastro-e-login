
# Projeto: Tela de Login com Python, MySQL e SQLAlchemy

## Objetivo

Este projeto visa desenvolver uma aplicação de login em **Python**, integrada ao banco de dados **MySQL** e utilizando **SQLAlchemy** para ORM. O projeto é estruturado com o padrão **MVC** e **POO** para promover organização e modularidade, sendo ideal para fins de prática e aprendizado.

## Estrutura do Projeto

```plaintext
projeto_login/
├── model.py               # Camada de Modelos (representação das tabelas do banco de dados)
├── view.py                   # Camada de Visualização (exibição de mensagens para o usuário)
├── controller.py          # Camada de Controle (lógica de negócio e comunicação entre Model e View)
└── README.md              # Documentação do projeto
```

## Funcionalidades

- **Cadastrar Usuário**: Realiza o cadastro de um novo usuário, verificando se o e-mail já está registrado e realizando validações básicas de nome e senha.
- **Login de Usuário**: Valida o e-mail e a senha do usuário, comparando o hash armazenado no banco com o fornecido no login.
- **Segurança de Senha**: Utiliza `hashlib` com algoritmo **SHA-256** para criptografar a senha antes de armazená-la no banco de dados.

## Tecnologias Utilizadas

- **Python 3.10**
- **MySQL** com **SQLAlchemy** para ORM
- **hashlib** para hash de senhas com **SHA-256**
- Arquitetura **MVC** e **POO**

## Configuração do Projeto

### Pré-requisitos

- **Python 3.10** instalado
- **MySQL** configurado e acessível
- Banco de dados MySQL para o projeto (ex: `aulapythonfull`)

Este projeto foi desenvolvido para fins de estudo e prática de conceitos de **POO**, **SQL**, arquitetura **MVC** e segurança em **Python**. 
