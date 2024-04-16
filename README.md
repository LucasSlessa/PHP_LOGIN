# Tela de Login PHP

Este repositório contém uma simples tela de login usando PHP e MySQL. A aplicação permite que os usuários façam login usando seus nomes de usuário e senhas cadastrados no banco de dados.

## Pré-requisitos

Certifique-se de ter o seguinte instalado em sua máquina:

- Servidor web (por exemplo, Apache)
- PHP
- MySQL

## Configuração do Banco de Dados

Execute o seguinte script SQL para criar a tabela `users` no seu banco de dados:

```sql
CREATE TABLE users (
    Id int PRIMARY KEY AUTO_INCREMENT,
    Username varchar(200),
    Email varchar(200),
    Age int,
    Password varchar(200)
);

```

## Configuração da Aplicação

1. Clone este repositório em seu servidor web.
2. Configure as credenciais do banco de dados no arquivo `config.php`.
3. Abra o arquivo `index.php` no seu navegador para acessar a tela de login.

## Funcionalidades

- Cadastro de novos usuários.
- Autenticação de usuários existentes.

## Tecnologias Utilizadas

- PHP
- MySQL
- HTML
- CSS

## Contribuição

Sinta-se à vontade para contribuir com novas funcionalidades, correções de bugs ou melhorias na aplicação.

