# Series Journal - Gestão de Séries Assistidas

**Aluna:** Karoline Costa Gonçalves

**Entrega:** Projeto Fase 2  


## 📋 Introdução

Este projeto consiste em uma aplicação web desenvolvida em React com Vite para a gestão de um diário de séries assistidas (*Series Journal*). O objetivo principal é demonstrar a integração de um frontend moderno com consumo de API REST (CRUD completo: Criar, Ler, Atualizar e Deletar), gerenciamento de estado, navegação com React Router e testes.


## Como Executar o Projeto

### Pré-requisitos
* Node.js instalado na máquina.
* Servidor backend `seriesjournal-api` rodando localmente.

### Passo a Passo

## Entre na pasta do projeto no terminal:
cd series-journal

## Rode npm install para instalar as dependências do projeto:
npm install

## Execute a API (Backend):
Em uma janela ou terminal separado, navegue até a pasta da API e inicie o servidor:

npm start

## Execute o Frontend:
No terminal do projeto principal, inicie a aplicação React/Vite:

npm run dev

## Após execução do projeto, este é o resultado esperado no navegador:
![Demonstração da Aplicação](./src/assets/video.gif)

## Como Executar os Testes
A aplicação utiliza Vitest e React Testing Library para a suíte de testes unitários dos componentes.
Para rodar os testes automatizados, abra o terminal na raiz do frontend e execute:

npm run test

## Descrição dos Componentes
A estrutura do projeto está organizada em páginas (./src/pages) e componentes reutilizáveis (./src/components):

**Páginas (src/pages)**:

- HomePage (/): Página inicial e de boas-vindas da aplicação.

- RegisterPage (/cadastrar): Página responsável por gerenciar o cadastro de novas séries.

- ListPage (/series): Exibe todas as séries cadastradas retornadas da API em formato de cards.

- EditPage (/editar/:id): Carrega os dados da série selecionada e permite alterar suas informações.

----

**Componentes (src/components)**:

- NavBar: Barra de navegação principal da aplicação utilizando React Router, permitindo navegação fluida entre as rotas (Home, Sobre, Cadastrar e Lista de séries).

- SerieForm: Formulário reutilizável com os 7 campos da série (Título, Número de temporadas, Diretor, Produtora, Categoria, Data de lançamento e Data em que assistiu). Suporta tanto criação quanto edição de registros.

- SerieCard / SerieList: Componentes responsáveis por renderizar os cards com os detalhes das séries e prover os botões para as ações de Editar (ícone do lápis) e Deletar (ícone da lixeira).


## 🏁 Conclusão
Este projeto demonstra a criação de uma interface dinâmica, acessível e funcional em ReactJS, contemplando a estruturação modular de componentes, o roteamento de páginas, a manipulação completa de dados via API e a validação de testes.




