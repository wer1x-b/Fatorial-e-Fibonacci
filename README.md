# Fatorial e Fibonacci

Este projeto é um pacote Python simples para calcular o fatorial de um número inteiro e o n-ésimo termo da sequência de Fibonacci.

## Estrutura

```
Fatorial-e-Fibonacci/
├── main.py
└── pacotes/
    ├── __init__.py
    ├── fatorial.py
    └── fibonacci.py
```

## Instalação

Clone o repositório ou baixe os arquivos.

## Como usar

No arquivo `main.py`:

```python
from pacotes import fatorial, fib

print(fib(10))        # Saída: 55
print(fatorial(5))    # Saída: 120
```
Sinta se livre para alterar os valores de nas funções `fib` e `fatorial` para testar com outros números.

## Funções

- `fatorial(n)`: Retorna o fatorial de `n`. Apenas para inteiros não negativos.
- `fib(n)`: Retorna o n-ésimo termo da sequência de Fibonacci. Apenas para inteiros não negativos.