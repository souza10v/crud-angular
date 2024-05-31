# CRUD em Angular - Projeto de Aprendizado

Este projeto foi desenvolvido com o objetivo de aprender e praticar os conceitos do framework Angular, criando uma aplicação CRUD (Create, Read, Update, Delete). O projeto abrange operações básicas de manipulação de dados e integração com uma API backend.

## Funcionalidades

- **Criação**: Adicionar novos itens à lista.
- **Leitura**: Visualizar a lista de itens.
- **Atualização**: Editar itens existentes.
- **Exclusão**: Remover itens da lista.

## Tecnologias Utilizadas

- **Angular**: Framework principal utilizado para o desenvolvimento da aplicação front-end.
- **TypeScript**: Linguagem utilizada para escrever o código da aplicação.
- **HTML/CSS**: Tecnologias usadas para a estrutura e estilização das páginas.
- **Bootstrap**: Biblioteca de CSS utilizada para a criação de uma interface responsiva.
- **JSON Server**: Ferramenta utilizada para simular um backend e fornecer uma API RESTful.

## Estrutura do Projeto

```plaintext
src/
├── app/
│   ├── components/
│   │   ├── create/
│   │   ├── read/
│   │   ├── update/
│   │   └── delete/
│   ├── services/
│   │   └── item.service.ts
│   ├── app-routing.module.ts
│   ├── app.component.html
│   ├── app.component.ts
│   └── app.module.ts
├── assets/
├── environments/
├── index.html
├── main.ts
└── styles.css
