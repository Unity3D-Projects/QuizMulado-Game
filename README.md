## QuizMulado (Versão Beta)

  **QuizMulado** é um aplicação mobile desenvolvida na Unity Engine utilizando **C#** como linguagem base, o objetivo do game consiste em responder perguntas no estilo *"Who Wants to Be a Millionaire"* de forma divertida e educativa.
  
### Arquitetura:

<p align="center">

<img src="https://github.com/DoisLucas/QuizMulado-Game/blob/master/architecture.png" width="100%" height="100%"/>

</p>

### Funcionamento:
  
Para cada acerto o jogador recebe uma quantia em moeda, e uma proxima pergunta é mostrada, a recompensa em moeda varia de acordo com o nivel de dificuldade da pergunta, para cada erro o jogador perde uma vida de um total inicial de cinco, acabando as vidas a partida se encerra, mostrando em seguida a pontuação obtida na partida. As pontuações são salvas no perfil do jogador fazendo com que cada vez mais o jogador se esforçe para quebrar seu record pessoal.

Com as moedas é possivel adquirir poderes na loja do game, dentre eles estão:

***PULO:*** Com o poder do pulo é possivel pular a pergunta atual.

***50/50:*** Duas alternativas erradas das 4 (totais) são descartadas.

***VIDA:*** O poder da vida adiciona mais uma vida permanentemente ao jogo.

***ESTATÍSTICA:*** Com o poder da estatÍstica é possivel resetar as estatisticas do jogador deixando suas moedas e poderes.

A partida começa com uma lista de perguntas, e ao errar, a pergunta entra no final da lista para ser respondida posteriormente, e as perguntas que são puladas com o poder, irão pra uma nova lista onda utiliza o mesmo mecanismo de erro, a nova lista será chamada logo após a primeira lista não ter nenhuma pergunta (certa ou errada) para ser respondida, lembrando que não existe a possibilidade de pular uma mesma pergunta duas vezes na mesma partida.

### Capturas de Tela:

<p align="center">

<img src="https://github.com/DoisLucas/QuizMulado-Game/blob/master/screenshots/screen2.gif" width="30%" height="30%"/>
<img src="https://github.com/DoisLucas/QuizMulado-Game/blob/master/screenshots/screen1.gif" width="30%" height="30%"/>
</p
