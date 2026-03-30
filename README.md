# Conjectura-de-Collatz-3n-1
📌 Descrição

Este projeto implementa um programa em Python para testar a Conjectura de Collatz em um intervalo de números inteiros. Para cada valor, o algoritmo aplica iterativamente a função definida até atingir 1, contabilizando o número de passos necessários.


🎯 Objetivo

Explorar a conjectura de Collatz e reforçar conceitos de programação em Python, com foco em eficiência e manipulação de estruturas de dados.


⚙️ Como funciona

Dado um intervalo [ini, fim], o programa:

Aplica a função:
n → n/2 (se n for par)
n → 3n + 1 (se n for ímpar)
Repete o processo até chegar em 1
Conta o número de passos para cada valor
Exibe o resultado no terminal


🚀 Otimizações

O algoritmo utiliza memoização (cache) para:

Armazenar resultados já calculados
Evitar recomputações
Melhorar o desempenho em intervalos grandes


📊 Observações

Alguns números geram sequências longas antes de convergir
O número de passos varia bastante entre valores próximos
Durante o processo, os valores podem crescer significativamente antes de diminuir


▶️ Como executar

python collatz.py
