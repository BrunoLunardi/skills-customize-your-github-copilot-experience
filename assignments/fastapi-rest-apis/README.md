# 📘 Assignment: Construindo APIs REST com framework FastAPI

## 🎯 Objective

Aprender a criar APIs REST utilizando o framework FastAPI, cobrindo conceitos como rotas, métodos HTTP, e validação de dados.

## 📝 Tasks

### 🛠️ Criar uma API Simples

#### Description
Crie uma API com FastAPI que tenha pelo menos duas rotas:
- Uma rota GET que retorna uma mensagem de boas-vindas.
- Uma rota POST que aceita dados JSON e retorna uma resposta com os dados recebidos.

#### Requirements
Completed program should:

- Ter um arquivo principal chamado `main.py`.
- Utilizar o FastAPI para definir as rotas.
- Incluir validação de dados para a rota POST.

### 🛠️ Adicionar Documentação Automática

#### Description
Utilize os recursos nativos do FastAPI para gerar documentação automática para a API.

#### Requirements
Completed program should:

- Expor a documentação no endpoint `/docs`.
- Utilizar o Swagger UI para visualização.
- Garantir que todas as rotas estejam documentadas corretamente.

### 🛠️ Testar a API

#### Description
Escreva testes para verificar o funcionamento das rotas criadas.

#### Requirements
Completed program should:

- Utilizar a biblioteca `pytest` para os testes.
- Testar pelo menos os seguintes cenários:
  - Resposta da rota GET.
  - Validação de dados na rota POST.
  - Resposta correta da rota POST com dados válidos.