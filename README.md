# DIO - Trilha .NET - Fundamentos
www.dio.me

## Desafio de projeto
Implementar funções para o sistema de estacionamento no módulo de fundamentos, da trilha .NET da DIO.

## Contexto
Eu fui contratado para construir um sistema para um estacionamento, que será usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Solução: 
Realizei as implementações solicitadas pelo curso, como realizar implementação da função que pega os dados digitados pelo usuário, utilizando o Console.ReadLine()

Fazer calculos de valor hora e valor final..

Adicionar e remover strings da List de placas.

Percorer a List com foreach.

E implementei duas funcionalidades que não estavam previstas no escopo inicial:

Validações idealizadas e implementadas por mim:

- O estacionamento não permite que mais de um veículo com a mesma placa seja inserido. Caso tente, ele retornará a mensagem "Este veículo já está estacionado. Digite outro" E não adiciona a lista de veículos adicionados.

- O estacionamento não permite que o usuário digite um texto em branco para a placa. Caso tente, ele retornará a mensagem "Você não digitou nenhum texto ou apenas espaços em branco." E não adiciona a lista de veículos adicionados.
