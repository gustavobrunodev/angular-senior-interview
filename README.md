## 🧪 Angular Senior Interview – Product Listing Challenge

Este repositório contém a base de um desafio técnico para desenvolvedores **Frontend Sênior (Angular)**.

### 💡 Desafio proposto:

> Criar um mini sistema de listagem de produtos consumindo dados de uma API pública.

### ✅ Requisitos

- Criar uma estrutura organizada com:
  - Módulo de produtos
  - Componentes: listagem e detalhes
  - Serviço para comunicação com a API
- Rota `/products`: listar produtos vindos da API [FakeStore](https://fakestoreapi.com/products)
- Rota `/products/:id`: exibir detalhes de um produto
- Usar `HttpClient` com `Observable`
- Navegação entre páginas com `RouterModule`
- **Criação de testes unitários**:
  - Testar o serviço (`ProductService`) para garantir o correto consumo da API.
  - Testar o componente de listagem de produtos (`ProductsListComponent`), verificando a renderização e a interação com o serviço.

### 🧱 Tecnologias utilizadas

- Angular
- Angular Material
- RxJS
- TypeScript
- Karma + Jasmine (testes unitários)
- FakeStore API

### 🎯 Objetivo da entrevista

Avaliar o domínio prático em Angular com foco em:
- Estruturação de aplicações em escala
- Organização de módulos e responsabilidades
- Consumo de APIs e manipulação reativa de dados
- Navegação entre rotas
- Escrita de testes unitários
