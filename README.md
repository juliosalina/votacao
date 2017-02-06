# Construindo uma Sistema de votação com RESTFull API - NodeJs - ExpressJs - MongoDb e ReactJs.

## Recursos utilizados no desenvolvimento:

- NodeJs;
- Express.Js ~ v.4.0;
- MongoDb;
- Mongoose ~4.x;
- Babel;
- React;
- SASS;
- NPM;
- Webpack;

## Testando a Aplicação no Postman:

Caso queira testar as API's criadas no projeto, primeiro baixe o [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop).
Depois de realizar o download do Postman, basta agora realizar os passos abaiaxo para 
poder testar cada API criada!

  ROTA                          |     HTTP(Verbo)   |      Descrição                           | 
--------------------------------| ----------------- | -----------------------------------------| 
/participantes                  |       GET         | Lista todos os participantes da votação  | 
/participantes                  |       POST        | Inserção do Participante na votação      | 
/participantes/:participante_id |       GET         | Selecionar Por Id                        | 
/participantes/:participante_id |       PUT         | Atualizar Por Id                         |
/participantes/:participante_id |       DELETE      | Excluir Por Id                           |

## Executar Localmente

Caso você deseja executar o projeto na sua máquina local, basta seguir os passos abaixo:

Você deve simplesmente clonar o repositório do projeto na sua máquina e instalar as dependências.

### Pre-Requisitos

Antes de instalar as dependências no projeto, você precisa já ter instalado na sua máquina:

* **NodeJs**: Caso não tenha, basta realizar o download [Aqui](https://nodejs.org/en/)

### Instalando as Dependências

Abre o terminal e digite a path onde clonou o repositório do projeto:

```
cd "C:\Users\NomeDoComputador\Documents\..."
```

Quando estiver na pasta do projeto (raiz), basta digitar no terminal a seguinte instrução:

```
npm install
```

Esse comando irá criar uma nova pasta em seu projeto, como descrito abaixo:

* `node_modules` - que contêm os packages do npm que precisará para o projeto.

### Executando a Aplicação

Bom, agora no terminal onde está aberto o projeto (raiz), basta iniciar o server para o projeto ser executado localmente.

```
node server.js
```

Agora, abra a página da aplicação em `http://localhost:8000/`. E pronto a aplicação será executada de maneira local na sua máquina.

PS: Caso queria ver o Webpack em funcionamento, que é uma função de desenvolvimento, para editar qualquer arquivo da aplicação, basta abrir um novo terminal na pasta do projeto (raiz) e digitar:

```
webpack -w
```     

Isso ira iniciar o Webpack, e a partir disso, sempre que você alterar e/ou salvar um arquivo, ele irá compilar com o Webpack e salvar os arquivos finais dentro da pasta ./public. 

Que a força esteja com você! :)
