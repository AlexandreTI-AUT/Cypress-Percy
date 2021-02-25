# curso-cypress-percy

Repositório do curso básico de testes de regressão visual com Cypress e Percy da [Escola Talking About Testing](https://talkingabouttesting.coursify.me).

## Pré-requisitos

Para instalar as dependências do projeto e executar os testes automatizados, é necessário que o [Node.js] ( https://nodejs.org/en/) e [NPM] (https://www.npmjs.com/) estejam instaldos em seu computador.

> Ao instalar o Node.js, o NPM é automaticamente instalado.

## Instalação

Após clonar o projeto, acesse o diretório do mesmo e execute `npm install` para instalar as dependências de desenvolvimento.

## Exportando o token do projeto criado no Percy.io

Exporte como uma variável de ambiente o token do seu projeto (disponível no _dashboard_ do Percy). Veja os exemplos abaixo para os sistemas Windows e Unix (Mac e Linux).

```
# Windows
$ set PERCY_TOKEN=<your token here>

# Unix 
$ export PERCY_TOKEN=<your token here>
```

> Fonte: https://docs.percy.io/docs/cypress

## Executando os testes

Execute o comando `npm test`para executar os testes em modo _headless_.
___

Um curso da [Escola Talking About Testing](https://talkingabouttesting.coursify.me).
