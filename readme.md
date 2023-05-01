#Key Ship War

#### Para ser vitorioso terá que ter muito vigor (e talvez um bom teclado). Key Ship War é um jogo multiplayer onde dois jogadores se enfrentam numa batalha na qual será o vencedor quem for o mais rápido e mais atento em apertar a tecla indicada pelo jogo, enquanto foi o seu turno, com cada tecla apertada é marcado um ponto para o jogador, vencendo que tiver o maior placar ao final do jogo. O jogador perde pontuação ao tentar alvejar o alvo quando seu turno termina, pois é suspensa um barreira defensiva na nave inimiga e seus tiros são ricocheteado. 


***


### Regras e Como foi utilizado Threads

* O jogo é baseado em turno, cada jogador só poderar atirar (apertar a tecla indicada), quando estiver no seu turno. Caso atire no turno do adversário, será retirado pontos do placar do jogador infrator.
* Cada tiro é um ponto para o placar do jogador
* O turno de cada usuário é uma thread. Uma thread é bloqueada para que a thread do segundo player seja executada.
* O jogo tem um marcador na tela que indica o turno do usuário. Deve se manter atento para não efetuar disparos no turno do inimigo

***

### Tecnologia
Essa é uma aplicação web que utiliza a linguagem java com o Spring Boot, utilizando WebSocket para a comunicação real time entre os jogadores e utilizando html e javascript para a construção da interface gráfica. 

***
*Criado por Emanuel Vieira, estudante da UFBA, matricula 219116800*