# gqs-algoritmo-02-py | Calculadora Simples
![Python Version](https://img.shields.io/badge/python-3.6+-blue.svg)
![Status](https://img.shields.io/badge/status-finalizado-brightgreen.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## O que o código faz?

Este programa é uma calculadora básica que realiza operações matemáticas simples entre dois números. O usuário pode inserir dois valores numéricos e escolher uma das quatro operações:
- **Adição** (+)
- **Subtração** (-)
- **Multiplicação** (*)
- **Divisão** (/)

## Detalhamento do Código

### Funções e Comandos Utilizados:

| Comando/Função | Descrição |
|----------------|-----------|
| `input()` | Captura dados inseridos pelo usuário via teclado |
| `float()` | Converte a entrada do usuário para número decimal (ponto flutuante) |
| `str()` | Converte a entrada para string (texto) |
| `if/elif/else` | Estruturas condicionais que direcionam o fluxo do programa baseado na operação escolhida |
| `print()` | Exibe mensagens e resultados no console |
| `f-string` | Formatação de strings que permite inserir variáveis diretamente no texto |

### Lógica do Programa:

1. **Entrada de Dados**: O programa solicita ao usuário dois números e a operação desejada
2. **Processamento**: Através de estruturas condicionais, identifica qual operação foi escolhida
3. **Validação**: Verifica se a divisão por zero está sendo solicitada
4. **Saída**: Exibe o resultado formatado ou uma mensagem de erro

### Tratamento de Erros:
- **Divisão por Zero**: Impedida através da condição `num2 != 0`
- **Operador Inválido**: Capturado pelo `else` final

## Exemplo de Saída

```
enter a number: 10
enter another number: 3
select a operator between (+, -, *, /): *

the result is: 30.0
```

### Outros Exemplos:

```
# Exemplo de Divisão
enter a number: 15
enter another number: 5
select a operator between (+, -, *, /): /

the result is: 3.0

# Exemplo de Tratamento de Erro (Divisão por Zero)
enter a number: 8
enter another number: 0
select a operator between (+, -, *, /): /

invalid operator or division by zero
```

## Sobre o Autor

Este projeto é uma atividade dada pelo [Prof. Daniel Paiva](https://github.com/danhpaiva) e foi projetada e documentada por Luiz Filipe Pimenta Correia
RA: 4261214196
* [Linkedin](www.linkedin.com/in/luiz-filipeBR)
* [GitHub](https://github.com/lufilipe123)
* [E-mail](luizfilipe.p.c@gmail.com)
