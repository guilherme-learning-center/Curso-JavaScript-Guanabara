# README do curso de fundamentos do JavaScript (Gustavo Guanabara)

# Aula 1: O que o JavaScript é capaz de fazer

* Client x Server
* Website é composto por basicamente 3 tecnologias:
  * Jornalista (**HTML**): escreve texto, usa imagens, cataloga vídeos e imagens etc.
  * Designer (**CSS**): pega as mídias e torna-se bonitas, organizando-as em formatos diferentes
  * Programador (**JavaScript**): trata da engenharia da entrega do jornal
* O HTML organiza os textos, o conteúdo
* O CSS pega o texto e o organiza para torná-lo mais agradável
* O JS faz as interações, como uma legenda em uma imagem, amplia uma imagem ao passar o mouse em cima dela etc. Ele inclusive modifica elementos escritos em HTML e CSS
* Quem utiliza o JS?
  * Google, YouTube, LinkedIn, Netflix etc.



# Aula 2: como chegamos até aqui

Um breve histórico do JavaScript — e da própria web em si.

# Aula 3: Dando os primeiros passos

## Como aprender?

* 💻 Assistindo aos vídeos das aulas
* ⌨️ Escrevendo código 
* 📒 Lendo livros sobre JS e outros materiais de referência
  * Livro: [JavaScript: O Guia Definitivo (David Flanagan)](https://www.amazon.com.br/JavaScript-Guia-Definitivo-David-Flanagan/dp/856583719X)
  * Livro: [JavaScript: Guia do Programador (Maurício Samy Silva)](https://novatec.com.br/livros/javascript-guia-programador/)
  * Livro: [JavaScript Eloquente - 2ª edição (Marijn Haverbeke)](https://github.com/braziljs/eloquente-javascript)
  * Guia de referência: [Referência JavaScript (Mozilla)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference)
  * Guia de referência: [ECMAScript® Language Specification](https://www.ecma-international.org/ecma-262/9.0/index.html#Title)
* 📘 Fazendo anotações (como esta) das aulas
* 👨‍👩‍👧‍👦 Interagindo com outras pessoas
  * Estudar em conjunto
  * Tirar dúvidas com outras pessoas
* 🖥 Desenvolver projetos próprios
  * Aplicar a ferramenta de programação para solucionar problemas reais do dia a dia

## Dúvidas comuns de quem está começando a programar

### 👨🏿‍🦳 Será que eu sou velho demais ou novo demais para começar a aprender a programar?

Não existe idade mínima e máxima para aprender. Cada um aprende. no seu ritmo. Além disso, não ouça pessoas que tentarem te convencer de que você está velho demais ou novo demais

### 👩🏾‍💻Programação não é 'coisa de homem'?

* Bom, pra começar a primeira linguagem de programação foi desenvolvida por uma matemática chamada [Ada Lovelace](https://pt.wikipedia.org/wiki/Ada_Lovelace). Historicamente, os primeiros profissionais de programação foram mulheres (Fonte: [Wikipedia](https://en.wikipedia.org/wiki/Women_in_computing)). Todos podem aprender a programar, independentemente de fatores como sexo, gênero, orientação sexual ou etnia. 

### 🌋"Eu preciso morar em uma cidade grande?"

Com a internet, o fator lugar deixa de ser tão relevante, pois todos em teoria têm acesso aos conteúdos "*core*", necessários ao aprendizado, disponibilizados online

### 🤓 Eu preciso ser 'nerd' para gostar de programar?

Não. Você só precisa querer aprender a programar. Ninguém é especial só porque sabe programar.

### 🇺🇸 É obrigatório ser bom em matemática e/ou ser bom em inglês para aprender a programar?

Há hoje ótimos materiais em português para quem está começando. E não é necessário ter aptidão para matemática para aprender, basta **querer** aprender.

### ♟  Aprender lógica de programação é perda de tempo?

Assim como, no filme Karate Kid, o personagem principal é colocado para aprender a pintar cerca para poder aprender Karatê, na programação, quando você aprende lógica, você aprende a moldar o seu *mindset*, o que tornará o seu processo de aprendizado mais assertivo.



### 💵  Todo programador ganha muito dinheiro?

Programadores iniciantes não vão ganhar muito dinheiro, nem o melhor emprego. Quando você tiver experiência, o seu salário não será mais seu objetivo, ele será sua consequência.

### 🏆 Qual a melhor linguagem de programação que existe?

A resposta é: nenhuma. Linguagens de programação cumprem propósitos específicos. Não seja o tipo de pessoa que defende uma linguagem em detrimento das demais.

### 📒 É mais fácil aprender JS através de frameworks?

Não. O ECMAScript/JavaScript é o ponto de partida de todo mundo que está querendo programar. Não tente partir da complexidade.

**Literalmente mundo um dia começou com um "Hello, world!".**

## Requerimentos de Software:

* Um computador
  * Um browser (Google Chrome, Firefox, Brave, Opera, Vivaldi etc.)
  * Um editor de código (Microsoft Visual Studio Code)
  * Node.js

# Aula 4: Criando seu primeiro script

Aprendemos onde a tag <style></style> fica no HTML e onde o <script></script> fica. Aprendemos também a usar o `window.alert()`, o `windw.confirm()` e o `window.prompt()`.



# Aula 5: Variáveis e tipos primitivos

## Adicionando comentários em JS:

Para comentar uma linha, utilize barras duplas:

````javascript
var testVar = "Variável de teste." // isto é um comentário em JS.
````

Para comentar duas ou mais linhas, utilize **barra + asterisco** para abrir e **asterisco + barra** para fechar:

````javascript
/* Isto é um comentário em uma linha.

JAVASCRIPTO EH TOPSTER <3

E isto é a linha final de um comentário. */

var testVar = "Isto é um código fora da área de comentários."; 
````

## Variáveis

* Um único sinal de igual (=) nunca é chamado de 'igual', mas sim de '**recebe**'.
* Se vocie atribui `Null` a uma variável, tudo dentro dela é destruído.

**Curiosidade**: No JavaScript moderno, além de utilizar a palavra **var**, também podemos usar a palavra **let** para definir variáveis.

````javascript
var n1 = 5
var n2 = 8.5
var n3 = 15

var s1 = "JavaScript"
var s2 = `Curso em vídeo`
var s3 = 'Guanabara'
````

### Identificadores

As variáveis se chamam identificadores, e eles possuem regras de formação.

* Variáveis podem começar com **letra**, **$** (cifrão) ou **_** (*underscore*).
* Não podem começar com **números**
* É possível usar **letras** ou **números**
* É possível utilizar **acentos** e **símbolos**
* Não podem conter **espaços**
* Não podem ser **palavras reservadas** (uma variável chamada `var`, por exemplo.)

### Node.js

#### Shell do Node.js no terminal:
![Shell do Node no Terminal](/Users/guiemi/github/guiemi-learning-center/javascript_guanabara/media/node_terminal.png)

#### Shell do Node.js no terminal do VSCode:
![Shell do Node no VSCode](/Users/guiemi/github/guiemi-learning-center/javascript_guanabara/media/node_vscode.png)

