# Arquitetura

* As funçoes relacionadas ao gerenciamento das casa do jogo da velha ficarão no módulo **jogodavelha.py**.

* o estado de cada casa do jogo será representadoa por uma string: "." para casa vazia; "X" para casa ocupada pelo 1° jogador; "O" para casa ocupada pelo 2° jogador

* A função inicializar() retornara uma lista 3x3, onde cada posição conterá uma string para indicar o estado de uma casa do jogo . A função retornará todas as casa inicialmente vazias.