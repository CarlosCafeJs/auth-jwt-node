# API de Autenticação com JWT

Esta é uma API simples de autenticação de usuários utilizando JSON Web Tokens (JWT) em Node.js. A API permite que os usuários façam login e obtenham um token de acesso para acessar rotas protegidas.

## Descrição

A API de Autenticação com JWT permite a criação de usuários e a autenticação via login
Esse token deve ser enviado no cabeçalho das requisições para que o servidor possa validar a autenticidade do usuário.

## Funcionalidades

- **Registrar Usuário**: Permite a criação de novos usuários.
- **Login de Usuário**: Autentica um usuário e retorna um token JWT.
- **Rota Protegida**: Exemplo de rota que requer autenticação via token JWT.

## Endpoints

- `POST /register`: Registra um novo usuário.
- `POST /login`: Autentica o usuário e retorna o token JWT.
- `GET /protected`: Rota protegida que só pode ser acessada com um token JWT válido.


