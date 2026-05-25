# Computer-Science-Algorithms

Este repositório é uma coleção de implementações de algoritmos e estruturas de dados fundamentais da Ciência da Computação, desenvolvidos para estudo e aprimoramento de lógica de programação. O objetivo é demonstrar a compreensão de diferentes abordagens para problemas clássicos, bem como a análise de complexidade de tempo e espaço.

## 📚 Conteúdo

### Algoritmos de Ordenação

| Algoritmo | Linguagem | Complexidade (Tempo ) | Complexidade (Espaço) | Descrição |
| :-------- | :-------- | :------------------- | :-------------------- | :-------- |
| **Bubble Sort** | Python | O(n²) | O(1) | Algoritmo simples que repetidamente percorre a lista, compara elementos adjacentes e os troca se estiverem na ordem errada. |
| **Selection Sort** | Python | O(n²) | O(1) | Encontra o menor elemento em cada iteração e o coloca na posição correta. |
| **Insertion Sort** | Python | O(n²) | O(1) | Constrói a matriz final um item por vez, inserindo cada novo elemento na posição correta entre os elementos já classificados. |
| **Merge Sort** | Python | O(n log n) | O(n) | Algoritmo de divisão e conquista que divide a lista em metades, ordena-as recursivamente e depois as mescla. |
| **Quick Sort** | Python | O(n log n) (médio) | O(log n) | Também de divisão e conquista, escolhe um 'pivô' e particiona a lista em torno dele. |
| **Counting Sort** | Python, MIPS Assembly | O(n + k) | O(n + k) | Algoritmo de ordenação não comparativo que funciona contando o número de ocorrências de cada item. |
| **Bucket Sort** | Python | O(n + k) (médio) | O(n + k) | Distribui os elementos em um número finito de 'baldes' e depois ordena cada balde individualmente. |

### Estruturas de Dados

*   **Listas Encadeadas**
*   **Pilhas (Stacks)**
*   **Filas (Queues)**
*   **Árvores (Trees)**

## 🚀 Como Utilizar

Cada algoritmo e estrutura de dados está contido em sua própria pasta, com um arquivo de código-fonte e, quando aplicável, um arquivo de teste.

```bash
# Exemplo: Executar Bubble Sort
cd algorithms/sorting/bubble_sort
python bubble_sort.py
