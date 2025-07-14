# LeetCode-Exercises5

## Lista de Exercícios - LeetCode (Programação Dinâmica)

**Número da Lista**: 5  
**Conteúdo da Disciplina**: Programação Dinâmica

## Alunos

| Matrícula   | Aluno                        |
| ----------- | --------------------------- |
| 200024949  | Matheus Ferreira Diogo      |

---

## Sobre

Resolução de questões do LeetCode (3 difíceis e 1 média) pelo integrante do grupo com o objetivo de demonstrar o conhecimento adquirido nesse módulo (Programação Dinâmica) da disciplina.

---

## Exercícios Resolvidos

### [32. Longest Valid Parentheses (Difícil)](https://leetcode.com/problems/longest-valid-parentheses/)  
Arquivo: [`32-LongestValidParentheses.py`](./32-LongestValidParentheses.py)  
Encontra o comprimento da substring de parênteses válidos mais longa. Utiliza uma pilha para rastrear índices e calcular o comprimento da substring válida mais longa em tempo O(n).

![32-LongestValidParentheses](/assets/32.PNG)

---

### [42. Trapping Rain Water (Difícil)](https://leetcode.com/problems/trapping-rain-water/)  
Arquivo: [`42-TrappingRainWater.py`](./42-TrappingRainWater.py)  
Calcula a quantidade de água que pode ser armazenada após chover em um mapa de elevação. Utiliza programação dinâmica para pré-computar os valores máximos à esquerda e à direita de cada posição.

![42-TrappingRainWater](/assets/42.PNG)

---

### [44. Wildcard Matching (Difícil)](https://leetcode.com/problems/wildcard-matching/)  
Arquivo: [`44-WildcardMatching.py`](./44-WildcardMatching.py)  
Implementa correspondência de padrões com wildcards ('?' e '*'). Utiliza programação dinâmica 2D para determinar se uma string corresponde a um padrão, com complexidade O(m*n).

![44-WildcardMatching](/assets/44.PNG)

---

### [64. Minimum Path Sum (Médio)](https://leetcode.com/problems/minimum-path-sum/)  
Arquivo: [`64-MinimumPathSum.py`](./64-MinimumPathSum.py)  
Encontra o caminho com soma mínima de cima-esquerda para baixo-direita em uma grade. Utiliza programação dinâmica in-place para otimizar o espaço, modificando a grade original.

![64-MinimumPathSum](/assets/64.PNG)

---

## Link da apresentação

[Link será adicionado após apresentação]

## Como Executar

**Linguagem**: Python

Execute cada arquivo separadamente para testar os exemplos:

```sh
python 32-LongestValidParentheses.py
python 42-TrappingRainWater.py
python 44-WildcardMatching.py
python 64-MinimumPathSum.py
```