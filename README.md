# MARIO JUMP

## TECNOLOGIAS UTILIZADAS
HTML, CSS e Javascript.

## COMO VISUALIZAR O PROJETO?
Acessando o link https://super-mariojump.netlify.app/

![image](https://media.discordapp.net/attachments/1112778878109356076/1113507198396551289/game.png?width=919&height=468)

## COMO FUNCIONA O PROJETO?
Mini game simples que utiliza DOM para realizar a manipulação do HTML e criar interatividade.


### DOM - MANIPULAÇÃO DO HTML ALTERNANDO CLASSES:
As imagens foram inseridas separadas das classes que contém as animações.

![image](https://media.discordapp.net/attachments/1112778878109356076/1113183381627355217/Imagens.png)

E as animações foram criadas dentro do CSS em classes distintas.

![image](https://media.discordapp.net/attachments/1112778878109356076/1113502581159891105/Animacoes.png?width=809&height=468)

No JavaScript foi inserido a função que une as duas classes no HTML. produzindo o efeito visual de saltar do personagem. 
A função setTimeOut foi utilizada para que após a execução da animação de salto, seja excluida a classe "Jump" do HTML, finalizando a animação.

![image](https://media.discordapp.net/attachments/1112778878109356076/1112800955877052507/Jump.png)

Ao ativar a função, no HTML a classe "jump" é removida pelo JavaScript ao final da duração da animação de salto.

![image](https://media.discordapp.net/attachments/1112778878109356076/1113514551846125618/mario-stop.png)

A função start é iniciada com pressionamento de qualquer tecla do teclado, substituindo a imagem do Mario parado para um gif do mesmo correndo, e iniciando as animações e sons de fundo.

![image](https://media.discordapp.net/attachments/1112778878109356076/1113513881957040268/finalizando_o_game.png)
