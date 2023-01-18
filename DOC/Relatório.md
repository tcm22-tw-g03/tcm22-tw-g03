# Relatório

<hr>


## Resumo do projeto:


Neste trabalho prático pretendemos expor os nossos conhecimentos e competências adquiridas na cadeira Tecnologias Web, desenvolvendo assim um espaço Web recorrendo à utilização de XML, HTML5, CSS e Javascript.

Decidimos então fazer um tema sobre tênis relacionando as novidades sobre o desporto, e assim desenvolver interesse a outros sobre o mesmo. 

A explicar um pouco deste tema temos como que o ténis é um desporto de origem inglesa, que é disputado em quadras, participando no jogo dois oponentes ou duas duplas de oponentes, podendo estas ser mistas ou não. É também um desporto considerado olímpico desde 1896 a 1924 (no género masculino) e desde 1988 (no género masculino e feminino). O mesmo possui um sistema de pontuação, que subdivide o jogo em jogos e sets, para marcar um ponto é preciso que a bola toque no solo em qualquer parte dentro da quadra adversária incluindo as linhas que estão ao longo do campo do oponente, fazendo com que o adversário não consiga devolver a bola antes do segundo toque, ou se conseguir que a devolva para fora dos limites dos restantes limites.

Nas páginas sugeridas HTML estáticas vamos abordar notícias mais atuais sobre o desporto em questão, mencionado notícias sobre jogadores e marcos importantes. Pretende-se referir regras e como este desporto funciona, incluindo informações das ligas profissionais e equipas, e por último o estado atual do desporto incluindo exemplos de jogadores e como esta modalidade está a chegar a novas alturas incluindo rankings básicos dos jogadores. Nesta parte do ficheiro HTML usaremos imagens dos jogadores como acontecimentos de jogo, usaremos tabelas para identificar os mesmos e organizar os dados de uma maneira mais apelativa.
Quanto ao XML e o Schema. Estes terão a informação corrida toda do HTML dividido por supostas páginas de maneira a já ter a informação organizada como serão os resultados mais recentes e rankings de jogadores, de maneira a estar tudo mais organizado.

<hr>

## Passos Iniciais:

Começamos por pesquisar sobre websites já existentes na internete para vermos como estes estariam formatados quanto às funcionalidades que têm.

Após alguma pesquisa começamos por fazer o index do website, criando um header e um footer bem como desenvolvendo uma coluna central para alinhamento geral de todo o website.

<hr>

### Header:!


No header procuramos ter um layout simples mas intuitivo que fosse apelativo ao utilizador, para tal escolhemos um beje escuro, para estar nivelada não sendo nem muito escura nem muito clara
![](https://i.imgur.com/ni7GvFp.png)

No mesmo escolhemos por o logo  do website bem como o nome do mesmo (TT Tenis Today)
![](https://i.imgur.com/OFLXroH.png) TT Tenis Today

Bem como as categorias/redirecionamentos que haveriamos a ter no website.

Para terminar o header decidimos implementar uma pequena sombra ao mesmo de maneira a dar uma separação menos agressiva para com o conteúdo do website.

<hr>

### Footer

No footer escolhemos implementar a mesma palete de cores, e nele inserimos icones que redirecionassem a diversas redes sociais bem como um butão "Back to Top" de maneira ao site ser mais prático para o utilizador.

<hr>

***Tanto o Header como o Footer, escolhemos que estes sejam fixos em todo o website uma vez que facilitam o uso do website devido às interligações que possuem.***

<hr>

## Index:

O index servirá como homepage do nosso site, nesta homepage temos um media, de maneira a ser uma introdução e ser mais atrativo seguido das notícias recentes do website, havendo estas alterar comforme a data de edição das notícias.

Cada notícia faz aparecer o seu título quando se der hover por cima da mesma, dando então uso de uma animação para embelezar o website.

De seguida temos uma comment box e um link de download do nosso XML.
A comment box, aquando o utilizador lhe der submit será redirecionado para uma nova página a dizer que foi submetido corretamente.

Esta página (REDIRECT.html) possui o mesmo header e o footer mencionado anteriormente.

<hr>

## Rules:

Nesta webpage começamos por, tal como no index, por um media, neste caso uma imagem na parte inicial da webpage, de seguida teriamos as regras do Ténis uma vez para melhor informar os utilizadores do website.

Nesta página inserimos também um botão que substitui o conteúdo do mesmo para mostrar uma imagem do court de Ténis.


<hr>

## News:

Nesta página temos as notícias elaboradas cada uma com o nome a aparecer aquando se faça hover em cima da mesma e cada uma com a devida ligação ao HTML da notícia.

<hr>

## News1, News2, News3, News4:

As notícias têm todas o mesmo layout sendo que cada uma dá uso de um dos termos pedidos no HTML desde vídeos e listas a tabelas.
![](https://i.imgur.com/NmDvOMB.png)
![](https://i.imgur.com/vZx15ar.jpg)

<hr>

## Rankings:

Os rankings mostra os top 12 jogadores de ténis com menções dos seus nomes e países de origem.
No Top 3 temos 3 medalhas (1st, 2nd e 3rd) que estariam no respetivo jogador.
![](https://i.imgur.com/QcWZKU0.png)

<hr>

## Recent Games:

Nesta Webpage temos jogos recentes com os jogadores envolvidos e os resultados defenidos pelo verde (vencedor) e vermelho (perdedor).

![](https://i.imgur.com/j5zI2uf.png)


<hr>

## Tournaments:

Nesta página temos diversos torneios mencionados bem como as suas localizações

<hr>

## Tell us more:

Esta webpage serviria como suporte que o utilizador escreveria um texto e submetia para a nossa base de dados como um xml porém não funciona corretamente.

<hr>
<hr>

# User Interface:

Na user interface procuramos criar algo simples, que não enchesse muito o website mas que fornecesse a informação total que pretendemos.

**Desenhamos esta wireframe inicial:**

Esta continha maioritariamente tudo o que pretendiamos para a homepage, servindo de base para as restantes páginas.
![](https://i.imgur.com/KJhj16E.jpg)

**UI Final**

![](https://i.imgur.com/KwgAkh8.jpg)

<hr>

## Website final:

O website serve então como meio de informação sobre novos acontecimentos de ténis.
O website pode ser aberto em qualquer browser bem como qualquer dispositivo.

As hiperligações existentes estão bem identificadas sendo de simples interpretação

Quanto a validações, no que toca a validação de formulários tentamos criar um xml que dividi-se a informação e torna-se numa tabela porém pensamos não estar a funcionar.

Quanto a validação geral do website temos um erro recorrente em todas as páginas devido a termos posto o logo criado para o website na própria tag do browser
![](https://i.imgur.com/jo7i9S3.png)

**O erro é o seguinte (presente em todas as webpages):
**
![](https://i.imgur.com/VzddkEc.png)
![](https://i.imgur.com/2E69Qx8.png)
![](https://i.imgur.com/c0xdgJ1.png)
![](https://i.imgur.com/3LCoZ9D.png)
![](https://i.imgur.com/sCcl7y7.png)
![](https://i.imgur.com/ccUvQjh.png)
![](https://i.imgur.com/66XJ7d8.png)


Trata-se portanto de um erro evitável caso se tire o código para fazer o pretendido porém pretendemos por esse logo.

<hr>


## Aspeto/Escolhas do Website

Quanto ao aspeto do site, usamos um site (https://www.sessions.edu/color-calculator/) para nos mencionar a cor que deviamos usar em contraste com a já mencionada ficando com as seguintes duas cores como cores principais
![](https://i.imgur.com/O1i6g8O.png)

E escolhemos escrever a preto uma vez  que é uma cor habitual e de fácil interpretação aos utilizadores


Aquando a realização do layout inicial consideramos usar o Holy Grail porém achamos que seria menos proveitoso para o nosso website uma vez que a coluna central seria mais pequena do que queríamos e achamos que acabariamos por não dar uso às colunas laterais logo escolhemos fazer uma coluna apenas sendo esta central e mais espaçosa

<hr>
