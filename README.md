# Posting Page

Projeto desenvolvido como parte do desafio de certificação, com o objetivo de criar uma página de postagem de blog utilizando HTML, CSS e JavaScript, realizando integração com uma API.

## Sobre o projeto

A aplicação permite ao usuário criar um post informando um título e um conteúdo. Ao enviar o formulário, os dados são enviados para uma API pública e o retorno é exibido na tela.

## Tecnologias utilizadas

- HTML5  
- CSS3  
- JavaScript  
- Fetch API  

## Funcionalidades

- Criação de post com título e conteúdo  
- Envio de dados para API externa  
- Renderização do post na tela  
- Limpeza automática do formulário após envio  

## Estrutura do projeto

- index.html  
- style.css  
- main.js  

## Como executar

1. Clone o repositório:
```
git clone https://github.com/seuusuario/posting--page
```

2. Acesse a pasta do projeto

3. Abra o arquivo `index.html` no navegador  
ou utilize o Live Server no VSCode

## API utilizada

https://jsonplaceholder.typicode.com/posts

## Como funciona

Ao enviar o formulário, é feita uma requisição POST para a API com os dados:

- title  
- body  
- userId  

Após o retorno da API, o título e o conteúdo são exibidos na página.

## Melhorias futuras

- Exibir múltiplos posts (feed)  
- Adicionar indicador de carregamento  
- Melhorar responsividade  
- Validação de formulário  

## Licença

Projeto para fins educacionais.