# Simulação REST API NodeJS   -  ![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=%20CONCLUÍDO&color=GREEN&style=for-the-badge)


### 1. Crie este repositório

* Faça o download do projeto
* Abra o VSCode 
* Abra a pasta extraída do github no VsCode (no link de referência acima)
* Abra o terminal do VsCode e insira os comando para criar o repositório na pasta:

 `git init`
 
 `git add .`
 
 `git commit -m "Iniciado projeto API e NodeJS"`

 `git branch -M main`
 
 `git remote add origin (inserir link de seu novo repositorio criado no github ex. https://github.com/seu_usuario/nome_repositorio.git)`

 `git push -u origin main`

### 2. Execute o servidor

 
- Abrir a pasta do projeto que você baixou e acessar o terminal do VSCode 
 
- Instale o servidor Json (API Local da sua máquina)
  
   `npm install -g json-server`

   
-  Execute o servidor com a base de dados

   `json-server --watch database.json`

## Acessando servidor local


- O servidor será executado em `http://localhost:3000`. Só abrir qualquer browser e digitar que será aberta a página inicial do API.

Você pode testar com o endpoint público: `http://localhost:3000/products` (método GET).

## Manipulando os dados
Com o Postment ou qualquer ferramenta de gestão de comunicação você pode alterar os dados de API, ou criar novas informações.

Para isso só utilizar os comandos abaixo.


#### Produtos

- Obter produtos: GET /produtos
- Obter produto por ID: GET /products/:id

#### Do utilizador

- Obter usuários: GET /users
- Obter usuário por ID: GET /users/:id
- Criar usuário: POST /users
- Atualizar usuário (informações completas): PUT /users/:id
- Atualizar usuário (informações parciais) PATCH /users/:id

#### Produtos
- Criar produto: POST /produtos
- Atualizar produto (informações completas): PUT /products/:id
- Atualizar produto (informações parciais) PATCH /products/:id


##### Exemplos de Filtros
- http://localhost:3000/users/
