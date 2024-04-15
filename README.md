# Simple Multiplayer Game Party

Reunir jogadores em volta de uma mesa virtual para jogar qualquer tipo de jogo.
Mover objetos na mesa, editar e compartilhar ideias num chat são uns dos principais recursos deste projeto.

## Simulador de bilhetes

Participantes podem mover e editar post-its pela tela

1. UserA cria um host, obtendo um ID da sala
2. UserB e UserC entram nesta sala, informando um nome e aguardando aprovação
3. UserA permite a entrada dos 2 participantes
4. UserA insere os elementos na mesa. Insere 4 post-its.
5. Os 3 participantes podem mover os post-its pela mesa. Podem editar o texto do post-it.
6. Todas as ações ficam registradas sequencialmente, permitindo ter um historico compartilhado e pedido de revisão.
7. Os registros são replicados na tela de todos os participantes.

## O desenvolvimento

Será utilizado Laravel como base de APIs, recepção dos movimentos e replicação
MySQL para armazenar os registros e controles
JQuery para mover elementos 
- https://jqueryui.com/draggable
- https://jqueryui.com/droppable

