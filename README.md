# repositorio-teste

Sistema de Grafos com Matriz de Adjacência em C

Descrição

Este projeto implementa um grafo não direcionado utilizando a linguagem C e a estrutura de matriz de adjacência. O sistema permite criar, modificar e visualizar grafos por meio de um menu interativo executado no terminal.

O objetivo do projeto é demonstrar a aplicação prática dos conceitos de Teoria dos Grafos e Estruturas de Dados, permitindo a manipulação de vértices e arestas, além da análise da estrutura do grafo.

Funcionalidades

Criar um grafo com quantidade definida de vértices.
Inserir arestas entre vértices.
Remover arestas existentes.
Limpar completamente o grafo.
Exibir a matriz de adjacência.
Calcular o grau de cada vértice.
Exibir a lista de adjacências.
Interface baseada em menu interativo.
Estrutura do Grafo

O grafo é representado por uma matriz de adjacência:

    0  1  2  3
0 [ 0  1  1  0 ]
1 [ 1  0  0  1 ]
2 [ 1  0  0  0 ]
3 [ 0  1  0  0 ]

Onde:

Valor 1 indica a existência de uma aresta.
Valor 0 indica ausência de conexão.

Como o grafo é não direcionado, a matriz é simétrica.
Tecnologias Utilizadas
Linguagem C
Biblioteca padrão stdio.h
Biblioteca padrão stdlib.h
Como Compilar

Utilizando GCC:

gcc grafo.c -o grafo
Como Executar

Linux/Mac:

./grafo

Windows:

grafo.exe
Menu do Sistema
===== MENU DO GRAFO =====
1 - Limpar grafo
2 - Inserir/remover aresta
3 - Mostrar matriz
4 - Mostrar graus
5 - Mostrar adjacencias
6 - Sair
Complexidade Computacional
Operação	Complexidade
Inserir aresta	O(1)
Remover aresta	O(1)
Verificar aresta	O(1)
Calcular grau	O(V)
Exibir matriz	O(V²)
Espaço utilizado	O(V²)

Autor
Eduardo Regis G. Nascimento
Projeto desenvolvido para a disciplina de Estruturas de Dados / Teoria dos Grafos do curso de Engenharia de Computação

Licença

Este projeto é destinado a fins acadêmicos e educacionais.
