## Sobre o projeto

Plataforma de consulta de contatos que permite ordenar de forma crescente e decrescente e pesquisar o seu contato através de seu nome.

## Tecnologias

Tecnologias utilizadas durante o projeto:

- [ReactJS](https://pt-br.reactjs.org/)
- [NodeJS](https://nodejs.org/en/)
- [JavaScript](https://www.javascript.com/)
- [Express](https://expressjs.com/pt-br/)
- [Docker](https://www.docker.com/)
- [Postgres](https://www.postgresql.org/)
- [Styled Components](https://styled-components.com/)
- [Eslint](https://eslint.org/)
- [EditorConfig](https://editorconfig.org/)

## Iniciando o projeto Local

Requerimentos: `node` , `yarn` e `docker`
- Instale as dependencias: `yarn`
- Inicie o serviço executando: `yarn dev`
- Baixe a imagem docker: `docker pull postgres`
- Crie o container: `docker run --name pg -e POSTGRES_USER=root -e POSTGRES_PASSWORD=root -p 5432:5432 -d postgres` 
- Iniciar container: `docker start pg`



