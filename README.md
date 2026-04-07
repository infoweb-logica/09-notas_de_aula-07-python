# Notas de aula de 2026.1.09 - Python 07

## Informações gerais

- **Público alvo**: alunos da disciplina de **Introdução a lógica e programação** do curso de [Infoweb](https://diatinf.ifrn.edu.br/cursos/tecnico-em-informatica-para-internet/) na [DIATINF](https://diatinf.ifrn.edu.br/) no [CNAT-IFRN](https://portal.ifrn.edu.br/campus/natalcentral/)
- **Professor**: [L A Minora](https://github.com/leonardo-minora/)
- **Objetivo**:
  1. Apresentar o conceito de estrutura de repetição
  2. Usar a instrução `while` para repetir um bloco de código
  3. Mostrar como contar usando a instrução `while`

---
## Notas de aula [slides pdf](/07-Estrutura_de_repetição-while-contar.pdf)
1. **Estrutura de repetição** é a estrutura que permite que um bloco de código seja executado mais de uma vez.
2. Em **Python** possui 2 instruções para defirnir uma estrutura de repetição: `while` e `for`
3. A estrutura para contar em python com a instrução `while`

```python
## estrutura geral para contar com while
contador = valor_inicial

while contador <= total:
  contador += incremento
  ## demais instruções
```

---
## Exercícios [Lista de exercícios](/lista.md)
1. Qual é a saída do programa a seguir?
```python
x = 0
while x < 4:
  print(x)
  x = x + 1
print("Fim")

```

2. Qual é a saída do programa a seguir?
```python
x = 1
while x <= 7:
  print(x)
  x = x + 2
print("Fim")

```

3. Qual é a saída do programa a seguir?
```python
x = 1
while x <= 5:
  print(x)
print("Fim")

```

4. Escreva um programa que imprime os números inteiros de 1 a 30.

5. Escreva um programa que imprime os números inteiros compreendidos no intervalo [-5; 5].

6. Escreva um programa que imprime os números pares compreendidos no intervalo [2; 10]

7. Escreva um programa que imprime os múltiplos de três compreendidos entre 1 e 20.

8. Programa FizzBuzz: escreva um programa que imprime os inteiros de 1 a 20 mas que **substitui**: 
   - os múltiplos de `3` pela palavra `Fizz`, 
   - os múltiplos de `5` pela palavra `Buzz`, e
   - os múltiplos de `3` e `5` pela palavra `FizzBuzz`.

9. Escreva um programa que tem como entrada um número inteiro positivo `numero` e imprime os números inteiros de 1 a `numero`.

| Exemplo de entrada | Saída esperada  |
| ------------------ | --------------- |
| 3                  | 1<br />2<br />3                      |
| 6                  | 1<br />2<br />3<br />4<br />5<br />6 |

10. Escreva um programa que tem como entrada um número inteiro positivo `numero` e imprime os números inteiros compreendidos no intervalo `[-numero; numero]`.

| Exemplo de entrada | Saída esperada  |
| ------------------ | --------------- |
| 2                  | -2<br />-1<br />0<br />1<br />2 |
| 1                  | -1<br />0<br />1                |

11. Escreva um programa que tem como entrada um número inteiro positivo `numero` e imprime os múltiplos de 3 compreendidos entre 1 e `numero`.

| Exemplo de entrada | Saída esperada  |
| ------------------ | --------------- |
| 7                  | 3<br />6                        |
| 15                 | 3<br />6<br />9<br />12<br />15 |

12. Programa FizzBuzz: Escreva um programa que tem como entrada um número inteiro positivo n e imprime os inteiros de 1 a n, mas que substitui os múltiplos de 3 pela palavra Fizz, os múltiplos de 4 pela palavra Buzz e os múltiplos de 3 e 4 pela palavra FizzBuzz.

| Exemplo de entrada | Saída esperada  |
| ------------------ | --------------- |
| 12                 | 1<br />2<br />Fizz<br />Buzz<br />5<br />Fizz<br />7<br />Buzz<br />Fizz<br />10<br />11<br />FizzBuzz |
