<h1 align="center">
      <a href="#" alt=> Hackathon de Inovação e Tecnologia </a>
</h1>


<h3 align="center">
     Hackathon Iblue desenvovido pelos estágiarios.
</h3>


    
    

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre o projeto](#-sobre-o-projeto)
   * [Como foi o desenvolvimento](#-desenvolvimento-do-Projeto)
   * [Regras de negócio](#-regras-de-negocio)
   * [Funcionalidades](#-funcionalidades)
   * [Como executar o projeto](#-como-executar-o-projeto)
     * [Pré-requisitos](#pré-requisitos)
     * [Tecnologias](#-tecnologias)
     * [Website](#user-content-website--react----typescript)
     * [Server](#user-content-server--nodejs----typescript)
<!--te-->





## 💻 Sobre o projeto

🏫 Simulador de Bônus -  É uma solução para fazer o acompanhamento das metas e fazer a simulação do bônus anual para todos os Ibluers.




## 💻 Desenvolvimento do Projeto
Esse projeto se deu inicio através de uma demanda onde foram passado para nós a documentação de como deveria ser a funcionalidade da aplicação, diante disso para poder iniciar esse projeto foi feito uma reunião para definir como seria a melhor maneira de desenvolver essa aplicação. Foram utilizados algumas ferramentas para ajudar no acompanhamento das fases do projeto. Uma dessas ferramentas que foi utilizada foi:

 
##    🖥️ Regras de negócio
####  🧍  Todo login é feito através da checagem de uma lambda responsavel por identificar se o usuário existe ou não; 
####  🧍  Todos os campos de cadastro são obrigatórios e não podem ficar vazios; 
####  🧍  Sempre que o usuário existir é gerado um token; 
####  🧍  O token é salvo no LocalStorage ou Cokkie do usuário; 
####  🧍  Todas as telas tem checagem de login; 




## ⚙️ Funcionalidades

- [x] Ao acessar a aplicação o usuário vai ser checado se existe ou não:
  - [x]  Vai gerar um Token 
  - [x]  Vai ser salvo no LocalStorage ou Cookies 



## 🚀 Como executar o projeto

Este projeto foi dividido em varias partes, para poder ser execultado :

1. BackEnd(API de Autenticação)

💡 O BackEnd para funcionar precisa ser execultado.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).[ Vue.js](https://vuejs.org/),[CLI AWS.ServerLess](https://aws.amazon.com/pt/cli/), Além disso é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/).


## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

-   **[AWS Lambda](https://aws.amazon.com/pt/lambda/)**
-   **[Node.JS](https://axios-http.com/ptbr/docs/intro)**
-   **[AWS DynamoDB](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/Introduction.html)**
-   **[SDK JAvaScript](https://aws.amazon.com/pt/sdk-for-javascript/)**
-   **[Chai](https://www.chaijs.com/)**
-   **[Mocha](https://mochajs.org/)**
-   **[Axios](https://axios-http.com/ptbr/docs/intro)**


#### **Utilitários**

-   Editor:  **[Visual Studio Code](https://code.visualstudio.com/)**





#### 🧭 Rodando a aplicação web (BackEnd)

```bash
# Clone este repositório
$ git clone https://git-codecommit.us-east-1.amazonaws.com/v1/repos/auth-users-api
# Acesse a pasta do projeto no terminal/cmd
$ cd iblue-school-front
# Instale as dependências
$ npm install ou yarn install
# Crie um arquivo .env na raiz do projeto
$ touch .env ou crie um arquivo pela IDE
# Vá para o arquivo .env.example
$ copie os dados do .env.example e cole no .env
# Altere os dados  .env 
$ Altere a porta ex: http://localhost:3000
# Execute a aplicação em modo de desenvolvimento
$ npm run serve ou yarn serve
# O servidor iniciará na porta:3000 por padrão - acesse http://localhost:9000
```

## 🦸 Desenvolvedores do Projeto
<br /> Diego Gonçalves da Fonseca <br /> <br /> Joana Linhares <br /> <br /> Matheus Saldanha <br /> <br /> Ulremberg Barbosa <br /> <br /> Wilson Pinheiro <br />


