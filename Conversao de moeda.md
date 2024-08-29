## 2. Conversão de Moeda

Este script converte um valor de Reais (BRL) para Dólares (USD) com base em uma taxa de câmbio fixa.

### Exemplo de Uso
O usuário fornece um valor em Reais, e o script converte para Dólares usando uma taxa de câmbio fixa de `1 USD = 5 BRL`.

### Código

```python
# Taxa de câmbio
taxa_cambio = 5.0  # 1 dólar = 5 reais

# Leitura do valor em reais
valor_reais = float(input("Digite o valor em reais: R$"))

# Conversão para dólares
valor_dolares = valor_reais / taxa_cambio

# Exibição do valor convertido
print(f"Valor em dólares: ${valor_dolares:.2f}")
