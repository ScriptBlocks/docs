# Capítulo 13: Tratamento de Erros e Exceções

Erros podem ocorrer durante a execução de um programa. Python fornece maneiras de lidar com essas exceções.

## Exemplo

```python
try:
    x = int(input("Digite um número: "))
except ValueError:
    print("Isso não é um número válido!")
```

Este código lida com o caso em que a entrada não é um inteiro válido.