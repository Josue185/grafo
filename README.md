#Objetivo
Este projeto simula uma rede social para explorar e analisar como as pessoas estão interconectadas. Utilizando a biblioteca NetworkX em Python, construí uma rede que representa indivíduos como nós e suas conexões como arestas. O projeto visa demonstrar conceitos fundamentais de teoria dos grafos, tais como caminhos, centralidade e comunidades dentro de uma rede social fictícia.

Tecnologias Utilizadas
Python: Linguagem de programação principal.
NetworkX: Biblioteca usada para criar, manipular e estudar a estrutura e a dinâmica de redes complexas.
Matplotlib: Biblioteca para visualização de dados em Python, utilizada para plotar o grafo.
Estrutura do Projeto
Criação do Grafo:

Inicializei um grafo não direcionado com a biblioteca NetworkX.
Adicionei nós que representam usuários da rede.
Adicionei arestas que representam as relações ou amizades entre os usuários.
Análise de Grafos:

![Screenshot 2024-04-17 15 43 56](https://github.com/Josue185/grafo/assets/92592495/0a31df38-79b9-4856-b222-e858c66da491)

![Screenshot 2024-04-17 15 43 41](https://github.com/Josue185/grafo/assets/92592495/89a7ffaa-435a-4fc7-832e-f74a0bb5eb16)


Grau de Nós: Calculei o número de conexões diretas que cada usuário tem, conhecido como grau do nó.
Caminho Mais Curto: Utilizei o algoritmo de Dijkstra implementado pelo NetworkX para encontrar o caminho mais curto entre dois usuários, demonstrando como informações ou influências podem fluir na rede.
Centralidade de Intermediação (Betweenness Centrality): Calculei a centralidade de intermediação para identificar usuários que servem como pontes entre diferentes grupos de usuários.
Detecção de Comunidades: Apliquei o algoritmo de modularidade de Clauset-Newman-Moore para identificar comunidades dentro da rede, ou seja, grupos de usuários mais densamente conectados entre si do que com o resto da rede.
Conclusão
Este projeto me permitiu não apenas compreender como os grafos são construídos e manipulados, mas também como algoritmos fundamentais funcionam, incluindo análises de caminho, centralidade e detecção de comunidades. Estes são conceitos essenciais em muitas áreas de pesquisa e desenvolvimento, desde análise de redes sociais até sistemas de recomendação e muito mais.
