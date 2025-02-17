# API DripStore

API desenvolvida como método de avaliação do encerramento do módulo backend do programa Geração Tech.

### Equipe:
- Antonio Neto
- Bruno Saraiva
- Rhayssa Costa
- Wanessa Loureiro

## 🚀 Instalação da aplicação

### Pré-Requisitos:

Antes de começar, você vai precisar ter instalado as seguintes ferramentas:
- [Git](https://git-scm.com) ou terminal de sua preferência;
- [Node.js](https://nodejs.org/en/)

### Clone o repositório:

#### Crie uma pasta no seu ambiente com o seguinte comando:
```
mkdir nome-da-pasta
```
Obs: É recomendado que o nome da pasta não contenha espaços ou caractéres especiais.

#### Acesse a pasta que criou com o seguinte comando:
```
cd nome-da-pasta
```

#### Dentro da pastta selecionada, execute o seguinte comando no seu terminal para baixar a aplicação:
```
git clone https://github.com/rhayssacosta/api-dripstore.git
```

### Instale as dependências:

```
npm i 
```

### Crie um arquivo .env e inclua as variáveis de ambiente. Dados que serão necessários:

- DB_NAME=example
- DB_USER=example
- DB_PASS=example
- DB_HOST=localhost
- DB_DIALECT=example
- PORT=3005
- KEY_SECRET=example

Obs: Campos que contém "example" será personalizado de acordo com o banco do usuário. 

### Para rodar o projeto, execute o comando:
```
$ npm start
```

### Visualizar API

- Via swagger:
  - http://localhost:3005/api-docs

- Via Insomnia ou Postman:
  - http://localhost:3005/api

### Executar end-point Users 

- Buscar todos os usuários (Método GET):
  - http://localhost:3005/api/users

- Buscar um único usuário pelo Id (Método GET):
  - http://localhost:3005/api/users/id
 
- Criar un novo usuário (Método POST):
  - http://localhost:3005/api/users
 
- Alterar um usuário pelo Id (Método PUT):
  - http://localhost:3005/api/users/id
 
- Excluir um usuário pelo Id (Método DELETE):
  - http://localhost:3005/api/users/id

Obs: Segue a mesma dinâmica de método e caminho para os end-points Product, Category, Order, ProductImages, Image, OptionsProduct, ProductCategory e Sale.
