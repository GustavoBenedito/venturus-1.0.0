# Projeto Venturus

## Projeto criado durante processo seletivo para vaga front-end do instituto Venturus.

Site sendo desenvolvido com HTML, CSS, JavaScript e com football API.

## Inicio

Iniciamos o código com a declaração Doctype, que serve para interpretadores de SGML consigam associar um DTD e verifica-lo.
A linguagem escolhida desse codigo foi o Inglês, portanto: "<html lang="en">"

### Na linha 10 temos o endereço da estilização do site feito através de código CSS.
## F#oi adicionado um script para podermos utilizar alguns icons da fontawesome.

# Header/Footer

![logo](https://github.com/Gustavobenedito64a/venturus-1.0.0/blob/main/imagens/imagens-readme/logo.png)
![login](https://github.com/Gustavobenedito64a/venturus-1.0.0/blob/main/imagens/imagens-readme/login.png)

o Header e o footer foi desenvolvido com a ideia de ser algo que poderia ser o mesmo codigo porem um na parte de baixo do site e o outro no topo, como se o header fosse identico ao footer.
Ele possui um roxo mais claro (rgba(192,14,78,1)) e através de um codigo de gradient ele irá escurecer até se tornar mais escuro (rgb(138,32,111)).

O login foi feito pensando em uma forma de fazer um circulo aonde guardaria as inicias de quem fez o login, por isso usamos um button com height width de 30px e um bom border-radius para deixar tudo redondo.


# body 
O body esta segurando todos os elementos de nosso site.

#main
O main possui nossas sections e foi estilisado para mante-las responsivas com display flex e um background com a cor #F7F3F7.

# section my teams

![myteams](https://github.com/Gustavobenedito64a/venturus-1.0.0/blob/main/imagens/imagens-readme/myteams.png)

A primeira section possui um titulo roxo, e uma tabela com alguns times que seriam usados a partir da API football, os icones foram usados nessa tabela para infatizar que teriamos como excluir, editar ou compartilhar um time. Além de possuir um botão para adicionar mais times.

# section top 5

![top5](https://github.com/Gustavobenedito64a/venturus-1.0.0/blob/main/imagens/imagens-readme/top5.png)

Essa section possui duas colunas que possuem 2 colunas, uma com times que estao em altas e outra que possui times que estao em baixa. Foi desenvolvida aonde cada time é uma div que possui bordas que se destacam quando passamos o mouse em cima de cada uma, a ideia era poder adicionar um link em cada div para direcionar ao time selecionado.


# section player

![player](https://github.com/Gustavobenedito64a/venturus-1.0.0/blob/main/imagens/imagens-readme/player.png)

A section player desenvolvida para parecer o maximo com o layout original, nao foi possivel ser 100% fiel mas foi feito o que foi possivel. Possui as bordas das partes superiores arredondas assim como o main. Player foi desenvolvido de uma forma que ao passar o mouse em cima de cada lado (most picked player e less picked player) a cor é mudada atraves do hover. A cor da section foi desenvolvida da mesma forma que foi feita o header e o footer.
