# Culinary Hub 🍽️ ![Em Desenvolvimento](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

O **Culinary Hub** é um sistema completo para gerenciamento de receitas, livros culinários, cozinheiros, degustadores e ingredientes. Desenvolvido para informatizar processos de uma empresa gastronômica, o sistema permite controle preciso de dados culinários e testes de qualidade.

## Tecnologias
![Tecnologias](https://skillicons.dev/icons?i=typescript,nestjs,postgres,docker,nodejs,react,vite,git)

## Índice

- [Culinary Hub 🍽️](#culinary-hub-)
  - [Tecnologias](#tecnologias)
  - [Índice](#índice)
  - [Sobre](#sobre)
  - [Funcionalidades](#funcionalidades)
  - [Instalação](#instalação)
  - [Uso](#uso)
  - [Licença](#licença)
  - [Contato](#contato)

## Sobre

O **Culinary Hub** foi criado com o propósito de centralizar e organizar receitas, ingredientes, livros culinários e os profissionais envolvidos em sua criação e avaliação. O sistema é dividido em backend e frontend, permitindo escalabilidade, segurança e manutenibilidade.

## Funcionalidades

- **Gerenciamento de Receitas**
  - CRUD completo de receitas com ingredientes e modo de preparo.

- **Livros Culinários**
  - Associação de receitas a livros publicados com controle editorial.

- **Cadastro de Profissionais**
  - Cozinheiros, editores e degustadores com seus respectivos papéis no sistema.

- **Testes de Qualidade**
  - Degustadores podem registrar avaliações e notas de receitas.

- **Controle de Ingredientes e Categorias**
  - Gestão de dados fixos utilizados nas receitas.

## Instalação

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/culinary-hub.git
   cd culinary-hub
    ```

2. Backend:

   ```sh
   cd backend
   cp .env.example .env
   docker-compose up --build
   ```

3. Frontend:

   ```sh
   cd ../frontend
   npm install
   npm run dev
   ```

> Acesse o frontend em `http://localhost:5173`
> Acesse a API em `http://localhost:3000` com Swagger em `/api`

## Uso

* O sistema pode ser usado por equipes editoriais, cozinheiros e degustadores.
* Possibilita gerenciar todo o fluxo de criação e publicação de receitas.
* Ideal para editoras de livros de culinária ou sistemas internos de controle gastronômico.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?\&style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/pedro-oliveira-m/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:pedro.oliveira@monteirodev.com)
