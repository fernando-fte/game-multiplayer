# 
O Jogo é composto por um Cliente e um Servidor,
Onde existe um servidor e vários clientes, imdependete de quem é.

# Responsabilidades
Camadas de responsábilidades são as definições da regra de negócio e onde será tratada cada tipo de elementos dentro de uma aplicação.


## Apresentação
Camada de apresentação visual para o cliente.
- Esta camada deve apenas exibir o jogo, sem possuir nenhuma regra de negócio
- iremos utilizar um canvaz para o game

## Lógica/Dados
Esta camada reserva de forma abstrata todas as informações do jogo e regras do jogo, e do tratamento de dados.

## Imputs
Esta camada é responsável por capturar os eventos do cliente e decide oque vai fazer no jogo.

## Network
Esta camada faz a comunicação entre os clientes e o server.


