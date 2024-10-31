# Problema: Soma de Dois Números Inteiros

## Descrição
Neste problema, você deve ler dois valores inteiros e calcular a soma entre eles. Em seguida, você deve imprimir o resultado de forma formatada.

## Entrada
O arquivo de entrada contém 2 valores inteiros \( A \) e \( B \).

## Saída
A saída deve ser formatada da seguinte forma:
```
SOMA = <resultado>
```
Onde `<resultado>` é a soma dos dois números. As palavras "SOMA" devem ser todas maiúsculas, e deve haver um espaço em branco antes e depois do sinal de igual. É importante lembrar de imprimir uma nova linha após o resultado para evitar o erro de "Presentation Error".

## Exemplo de Entrada
```
5
10
```

## Exemplo de Saída
```
SOMA = 15
```

## Resolução
1. Leia os dois números inteiros da entrada.
2. Calcule a soma dos dois números.
3. Imprima a soma no formato especificado.

## Implementação em Python
Abaixo está uma possível implementação em Python 3.9:

```python
# Leitura dos valores inteiros A e B
A = int(input())
B = int(input())

# Cálculo da soma
SOMA = A + B

# Impressão do resultado
print(f"SOMA = {SOMA}")
```

## Considerações
- Certifique-se de que a saída esteja no formato correto para evitar erros de apresentação.
- Teste o programa com diferentes valores para garantir que a soma está sendo calculada corretamente.
```

### Como Usar o README
1. **Descrição**: Apresenta um resumo do que o problema envolve.
2. **Entrada/Saída**: Define claramente o que deve ser esperado.
3. **Exemplos**: Fornece exemplos práticos para ilustrar o funcionamento.
4. **Resolução**: Explica a lógica de solução e fornece um exemplo de código.
5. **Considerações**: Inclui dicas para evitar erros comuns.
