# Numero-Fatorial

# Calculadora Fatorial

Este programa em C permite calcular o fatorial de um número inteiro fornecido pelo usuário.

## Requisitos

Para compilar e executar este programa, é necessário um compilador C instalado no seu sistema. Você pode usar o GCC ou outro compilador de sua preferência.

## Como Usar

1. Clone este repositório ou baixe o arquivo `codigo.c`.
2. Abra um terminal e navegue até o diretório onde o arquivo `codigo.c` está localizado.
3. Compile o código-fonte usando o seguinte comando:

    ```
    gcc codigo.c -o calculadora_fatorial
    ```

4. Execute o programa recém-compilado:

    ```
    ./calculadora_fatorial
    ```

5. Siga as instruções exibidas no console para inserir o número para o qual você deseja calcular o fatorial.
6. O programa calculará o fatorial do número fornecido e exibirá o resultado.

## Exemplo

```
Digite um valor:
5
5! = 120
```

## Observações

- Este programa verifica se o número fornecido pelo usuário é maior ou igual a zero. Se for menor que zero, exibe uma mensagem de erro.
- O fatorial de um número inteiro não negativo n é o produto de todos os inteiros positivos menores ou iguais a n. O fatorial de 0 é definido como 1.
- Este programa não lida com números muito grandes que possam exceder o intervalo suportado pelos tipos de dados inteiros em C.


