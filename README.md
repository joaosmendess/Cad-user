# Backend do Projeto CAD-USER

Bem-vindo ao repositório do backend do ProjetoCAD-USER. Este backend é responsável por gerenciar dados de usuários em um banco de dados MySQL e expor uma API para interação com o frontend.

## Tecnologias Utilizadas

- Node.js: Plataforma de execução de JavaScript.
- Express.js: Framework web para Node.js.
- MySQL: Banco de dados relacional.
- Cors: Middleware para lidar com a política de mesma origem.
- Outras dependências: Consulte o arquivo `package.json` para obter uma lista completa.

## Configuração

1. **Instalação de Dependências:** Execute `npm install` para instalar todas as dependências necessárias.

2. **Configuração do Banco de Dados:** Configure as informações do seu banco de dados MySQL no arquivo `db.js`.

3. **Iniciar o Servidor:** Execute `npm start` para iniciar o servidor na porta 8800.

## Funcionalidades

Este backend oferece as seguintes funcionalidades:

- [x] Criar um novo usuário.
- [x] Obter todos os usuários.
- [x] Atualizar os detalhes de um usuário existente.
- [x] Excluir um usuário existente.

## Estrutura do Projeto

A estrutura de pastas do projeto é organizada da seguinte maneira:

- `controllers`: Contém os controladores para lidar com as operações CRUD.
- `routes`: Contém as definições de rotas para as operações CRUD.
- `db.js`: Arquivo de configuração do banco de dados.
- `app.js`: Arquivo principal que configura o servidor Express.

## Exemplos de Uso

Você pode usar o Postman ou outra ferramenta semelhante para testar as rotas da API. Aqui estão alguns exemplos de como usar as rotas:

- `GET /`: Obter todos os usuários.
- `POST /`: Adicionar um novo usuário.
- `PUT /:id`: Atualizar um usuário existente com base no ID.
- `DELETE /:id`: Excluir um usuário existente com base no ID.
