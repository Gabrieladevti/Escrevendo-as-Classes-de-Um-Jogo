# Desafio Escrevendo as classes de um jogo

 Neste desafio deve ser explorado os conceitos como variáveis, operadores, loops  estruturas de decisão, funções e classes em especial.

## Objetivo

Crie uma classe generica que represente um herói de uma aventura e que possua as seguintes propriedades:

- nome
- idade
- tipo (ex: guerreiro, mago, monge, ninja )


Além disso, deve ter um método chamado atacar que deve atender os seguientes requisitos:

* exibir a mensagem: "o {tipo} atacou usando {ataque}")
* aonde o {tipo} deve ser concatenando o tipo que está na propriedade da classe
* e no {ataque} deve seguir uma descrição diferente conforme o tipo, seguindo a tabela abaixo:

  - se mago -> no ataque exibir (usou magia)
  - se guerreiro -> no ataque exibir (usou espada)
  - se monge -> no ataque exibir (usou artes marciais)
  - se ninja -> no ataque exibir (usou shuriken)

## Saída

Ao final deve se exibir uma mensagem:

- "o {tipo} atacou usando {ataque}"
    - ex: mago atacou usando magia 
    - guerreiro atacou usando espada

## Execução
Digite no terminal `node index.js`