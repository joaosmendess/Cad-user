# Frontend do Projeto CAD-USER

Bem-vindo ao repositório do frontend do Projeto CAD-USER. Este frontend é responsável por interagir com o backend para gerenciar dados de usuários em um banco de dados MySQL.

## Tecnologias Utilizadas

- React.js: Biblioteca JavaScript para criar interfaces de usuário.
- Axios: Biblioteca para fazer requisições HTTP para o backend.
- Styled-components: Biblioteca para estilizar componentes usando CSS no JavaScript.
- React-toastify: Biblioteca para exibir notificações na interface do usuário.
- Outras dependências: Consulte o arquivo `package.json` para obter uma lista completa.

## Configuração

1. **Instalação de Dependências:** Execute `npm install` para instalar todas as dependências necessárias.

2. **Configuração da API:** Verifique e ajuste a URL da API no arquivo onde você faz as chamadas para o backend.

3. **Iniciar o Frontend:** Execute `npm start` para iniciar o servidor de desenvolvimento na porta 3000 (ou outra porta, dependendo da configuração).

## Funcionalidades

Este frontend oferece as seguintes funcionalidades:

- [x] Exibir uma lista de usuários.
- [x] Adicionar um novo usuário.
- [x] Editar os detalhes de um usuário existente.
- [x] Excluir um usuário existente.

## Estrutura do Projeto

A estrutura de pastas do projeto é organizada da seguinte maneira:

- `src/components`: Contém os componentes React reutilizáveis.
- `src/pages`: Contém as páginas principais do aplicativo.
- `src/services`: Contém a lógica para fazer chamadas à API do backend.
- `src/App.js`: Arquivo principal que configura a interface do usuário.

## Exemplos de Uso

Você pode usar a interface do usuário para interagir com os dados de usuários. Aqui estão alguns exemplos de como usar as funcionalidades:

- Abra o aplicativo no navegador.
- Visualize a lista de usuários.
- Clique em "Adicionar Usuário" para criar um novo usuário.
- Clique em "Editar" ao lado de um usuário para editar seus detalhes.
- Clique em "Excluir" ao lado de um usuário para removê-lo.
