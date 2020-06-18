<h1>Desafio Back-end: Conceitos de Node.js</h1>

<h4>Esse repositório é referente ao primeiro desafio do Bootcamp GoStack turma 12, oferecido pela <a href="https://rocketseat.com.br/">Rocketseat </a>.</h4>

Nele aplicamos um pouco do conhecimento adquirido no *primeiro módulo* do curso => **Back-end: Conceitos de Node.js**

Recebemos o template abaixo e o editamos para que atendesse aos requisitos propostos

<img src="https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/desafio-conceitos-nodejs/assets/nodejs-example.png" />

```POST /repositories:``` A rota deve receber title, url e techs dentro do corpo da requisição, sendo a URL o link para o github desse repositório. Ao cadastrar um novo projeto, ele deve ser armazenado dentro de um objeto no seguinte formato: 
```
{ 
		id: "uuid", 
		title: 'Desafio Node.js', 
		url: 'http://github.com/...', 
		techs: ["Node.js", "..."], 
		likes: 0 
};
```
Certifique-se que o ID seja um UUID, e de sempre iniciar os likes como 0.

```GET /repositories:``` Rota que lista todos os repositórios;

```PUT /repositories/:id:``` A rota deve alterar apenas o title, a url e as techs do repositório que possua o id igual ao id presente nos parâmetros da rota;

```DELETE /repositories/:id:``` A rota deve deletar o repositório com o id presente nos parâmetros da rota;

```POST /repositories/:id/like:``` A rota deve aumentar o número de likes do repositório específico escolhido através do id presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes deve ser aumentado em 1;

## Tecnologias Usadas
- JavaScript
- Node.js
- Nodemon
- Express
- cors
- uuId
- Teste automatizados

Concluído no dia: **17/06/2020**
