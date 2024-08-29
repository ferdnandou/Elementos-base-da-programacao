# Cálculos Básicos em Python

Este projeto contém uma série de scripts Python para realizar cálculos matemáticos básicos, como cálculo da área de um círculo, conversão de moedas, operações matemáticas, cálculo de salário líquido e projeção de idade.

## Scripts

### 1. Cálculo da Área de um Círculo

Este script calcula a área de um círculo com base no raio fornecido pelo usuário.

#### Código
```python
import math

# Constante para o valor de pi
PI = 3.14159

# Leitura do raio
raio = float(input("Digite o raio do círculo: "))

# Cálculo da área
area = PI * (raio ** 2)

# Exibição da área
print(f"A área do círculo é: {area:.2f}")
