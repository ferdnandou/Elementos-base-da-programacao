## 3. Operações Matemáticas Simples

Este script realiza operações matemáticas básicas (adição, subtração, multiplicação e divisão) entre dois números.

### Exemplo de Uso
O usuário fornece dois números e uma operação (+, -, *, /). O script executa a operação correspondente.

### Código

```python
# Leitura dos números e operação
numero1 = float(input("Digite o primeiro número: "))
numero2 = float(input("Digite o segundo número: "))
operacao = input("Digite a operação (+, -, *, /): ")

# Realização da operação
if operacao == '+':
    resultado = numero1 + numero2
elif operacao == '-':
    resultado = numero1 - numero2
elif operacao == '*':
    resultado = numero1 * numero2
elif operacao == '/':
    if numero2 != 0:
        resultado = numero1 / numero2
    else:
        resultado = "Erro: Divisão por zero"
else:
    resultado = "Operação inválida"

# Exibição do resultado
print(f"Resultado: {resultado}")
```
