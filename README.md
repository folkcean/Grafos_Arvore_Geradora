# Grafos_Arvore_Geradora
Trabalho prático da disciplina de Grafos - Implementação dos algoritmos de Prim, Kruskal e Boruvka

# LE1 - Implementação de Algoritmos de Árvore Geradora 

Repositório destinado à implementação da Lista de Exercícios 1 da disciplina de Algoritmos em Grafos do curso de Ciência da Computação da UENF.

## Objetivo
Implementar em Python os algoritmos de Prim, Kruskal e Boruvka/Sollin para calcular a Árvore Geradora Mínima (MST) de grafos não direcionados com pesos.

## Checklist de Implementação e Tarefas

### 1. Estruturação Básica
- [x] Definição da classe `Grafo` com suporte a vértices e arestas.
- [x] Representação computacional escolhida: Lista de Adjacência (Dicionário) e Lista de Arestas (Tuplas).
- [x] Função geradora de grafos não direcionados e conexos com pesos aleatórios.

### 2. Bateria de Testes (Gerador)
- [x] Geração de grafos Densos completos (n*(n-1)/2) arestas.
- [x] Geração de grafos Esparsos (n*4/2) arestas.
- [x] Teste de integridade de criação para n = 10 vértices.

### 3. Algoritmos de Árvore Geradora Mínima (MST)
- [ ] Implementação do Algoritmo de Prim.
- [ ] Implementação do Algoritmo de Kruskal.
- [ ] Implementação do Algoritmo de Boruvka/Sollin.

### 4. Análise e Visualização
- [ ] Coleta do tempo de execução de cada algoritmo.
- [ ] Tabela comparativa de desempenho entre os três métodos para grafos densos e esparsos.
- [ ] Função para desenhar visualmente o grafo original G e a árvore geradora T (para grafos menores).
