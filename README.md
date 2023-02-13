
# Projeto Individual - Estão sevidos?

Este é um projeto do curso de WebDev da Resilia Educação, o objetivo tem como o desenvolvimento de um micro-servidor utilizando a lib JSON-Server para simular um banco de dados com modelagem CRUD (Create, Read, Update e Delete), inicialmente com 3 rotas e 4 métodos (GET, POST, PATCH e DELETE) em um arquivo JSON.



## Documentação

[Documentação - NPM Json-server](https://www.npmjs.com/package/json-server#getting-started)

As rotas definem como você vai acessar a API.
As rotas são:

| request  | URL       | detalhes                          |
| :---------- | :--------- | :---------------------------------- |
|GET	|farmacia	|Busca todos os produtos|
|GET	|farmacia/1	|Busca um produto|
|POST	|farmacia	|Salva um produto|
|PUT	|farmacia/1	|Atualiza dos os dados da farmacia|
|PATCH	|farmacia/1	|Atualiza parte dos dados da farmacia|
|DELETE	|farmacia/1	|Remove um produto|


## Instalação

Os requisitos para executar o projeto é ter ele clonado em sua maquina clique em code logo acima no canto superior direito, e copie o ssh ou https ou github cli e entre no seu terminal de preferencia e use o comando 
```bash 
git clone
```

Logo apos clonar o repositorio use o comando em seu terminal:
```bash
$npm install
```
para mais informações use o guia: [Alura NPM](https://www.alura.com.br/artigos/como-instalar-node-js-windows-linux-macos?gclid=CjwKCAiA85efBhBbEiwAD7oLQGKTsA4_ipo8u2QxYO6COv6O_oxsgHPfKtkMZcvaD3X20tsBB5WM4RoCQ1AQAvD_BwE)

## Apos a instalação temos que instalar o json server utilize o comando 
```bash
$npm i json-server 
```
Em seguida utilize:
```bash
 $npx json-server --watch database.json
```
Para acessar as rotas, em seu terminal
    
## Insomnia

Para acessar as rotas do arquivo JSON pelo Insomnia e fazer alterações no arquivo, siga as instruções abaixo:

Primeiramente para utilizar o Insomnia, acesse https://insomnia.rest/, clique em: Get Start For Free e clique em: Download; em seguida será encaminhado a pagina de download, clique em: Download Insomnia For Windows e execute para instalar.

Após a instalação, 

## Com o Insomnia aberto

Adicione uma nova pasta a seu insomnia e selecione a opção de **importação** e selecione o arquivo 
 ```bash
 Insomnia_Individual_3
`````

Agora só testar a funcionalidade do projeto!
## Stack utilizada

**Back-end:** Node.js

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white "node Js") 

## Autor: Thiago Soares

- [Github](https://github.com/ThiagoMSo)
- [Linkedin](https://www.linkedin.com/in/thiagom-soares/)
- [Instagram](https://www.instagram.com/thiago_soares3/)

