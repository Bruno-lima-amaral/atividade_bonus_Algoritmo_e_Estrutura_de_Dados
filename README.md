# README – Lista de Exercícios de Lista de Prioridade (Java)

Este documento serve como um guia organizado e simples para entender e resolver os exercícios da "Lista de Exercícios de Lista de Prioridade em Java" do Prof. Odair.

## 📘 Conteúdo

A lista contém **5 exercícios** envolvendo estruturas de prioridade (Heaps) e aplicações práticas em Java.

---

## 📝 Exercício 1 – Encontrar os K maiores elementos

**Objetivo:** Utilizar um **Min-Heap** para encontrar rapidamente os *K* maiores elementos de um array.

* Criar o método: `findKthLargest(int[] arr, int k)`
* Complexidade esperada: **O(N log K)**

---

## 📝 Exercício 2 – Mesclar K listas ordenadas

**Objetivo:** Usar um **Min-Heap** para juntar várias listas ordenadas em uma única lista também ordenada.

* Criar o método: `mergeKSortedLists(List<List<Integer>> lists)`
* Dica: armazenar no heap um objeto com (valor, índice da lista, índice interno)

---

## 📝 Exercício 3 – Lista de Prioridade Dupla

**Objetivo:** Criar uma estrutura capaz de retornar/remover **mínimo e máximo** rapidamente.

* Criar a classe `DualPriorityQueue`
* Deve conter:

  * `insert(int value)`
  * `getMax()`
  * `getMin()`
  * `removeMax()`
  * `removeMin()`
* Usar **duas PriorityQueue** (Min-Heap e Max-Heap) + **HashMap de frequência**

---

## 📝 Exercício 4 – Verificar se um array é Min-Heap

**Objetivo:** Confirmar se um array representa um Min-Heap válido.

* Criar o método: `isMinHeap(int[] arr)`
* Verificar se para todo índice `i`: `arr[i] <= arr[2*i+1]` e `arr[i] <= arr[2*i+2]`
* Complexidade: **O(N)**

---

## 📝 Exercício 5 – Encontrar a mediana em um fluxo de dados

**Objetivo:** Manter um fluxo de inteiros enquanto calcula a mediana em tempo eficiente.

* Criar a classe `MedianFinder`

  * `addNum(int num)`
  * `findMedian()`
* Usar:

  * **Max-Heap** → metade menor
  * **Min-Heap** → metade maior

---
