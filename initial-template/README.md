# JSExpertMax Gesture Controller - Semana JS Expert 7.0

Antes de mais nada, utilize os comandos abaixo para controlar a página.

    'scroll-down': '✊️' - Rolar a página para baixo.
    'scroll-up': '🖐' - Rolar a página para cima.
    'click': '🤏' - Controle de click.
    'rock': '🤘' - Este controlole não afeta a página.

## Preview
<img width=100% src="./assets/demo-template-lg.gif">

## Pre-reqs

- Este projeto foi criado usando Node.js v19.6

## Running

- Execute `npm ci` para restaurar os pacotes
- Execute `npm start` e em seguida vá para o seu navegador em [http://localhost:3000](http://localhost:3000) para visualizar a página acima

## Checklist Features
- Titles List
  - [x] - Campo para pesquisa não deve travar ao digitar termo de pesquisa
  - [x] - Deve desenhar mãos na tela e fazer com que elementos em segundo plano  continuem sendo clicáveis  🙌
  - [x] - Deve disparar scroll up quando usar a palma das mãos abertas 🖐
  - [x] - Deve disparar scroll down quando usar a palma das mãos fechadas ✊
  - [x] - Deve disparar click no elemento mais próximo quando usar  gesto de pinça 🤏🏻
  - [x] - Ao mover elementos na tela, deve disparar evento **:hover** em elementos em contexto

- Video Player
  - [x] - Deve ser possivel de reproduzir ou pausar videos com o piscar de olhos 😁
  - [x] - Todo processamento de Machine Learning deve ser feito via Web worker

### Desafios
- [x] - Aula 01 - Diferenciar piscada de olhos entre olho direito e esquerdo e atualizar log para mostrar qual olho que piscou.
- [x] - Aula 02 - Reconhecer gestos de mãos individuais e printar no log
- [x] - Aula 03 - A definir
- [x] - Aula 04 - A definir

### Créditos ao Layout
- Interface baseada no projeto [Streaming Service](https://codepen.io/Gunnarhawk/pen/vYJEwoM) de [gunnarhawk](https://github.com/Gunnarhawk)

- Curso criado por Erick Wendel.