# SeminarioAutomatos-ExpressoesRegulares

- Lucas Lourenço de Lima - 01588150
- Amhos Cezar Carneiro de Moraes - 01589117



# Expressões Regulares, Linguagens Formais e Autômatos

Este repositório contém materiais relacionados ao estudo de **Expressões Regulares**, **Linguagens Formais** e **Autômatos**, fundamentais para a **Teoria da Computação** e **Linguagens Formais**.

## Conceitos Principais

### 1. Expressões Regulares
As **expressões regulares** são usadas para descrever **linguagens regulares**. Elas utilizam operadores como:

- **Concatenação**: Junção de cadeias. Exemplo: `AB`.
- **União**: Escolha entre alternativas. Exemplo: `A | B`.
- **Fecho de Kleene**: Zero ou mais repetições. Exemplo: `A*`.

#### Exemplo
A expressão regular `(a|b)*c` representa a linguagem que contém qualquer combinação de `a`s e `b`s, seguida de `c`.

### 2. Linguagens Formais
Uma **linguagem formal** é um conjunto de cadeias sobre um alfabeto `Σ`. As linguagens são classificadas pela **Hierarquia de Chomsky**:

- **Linguagens Regulares**: Descritas por expressões regulares, reconhecidas por **Autômatos Finitos**.
- **Linguagens Livres de Contexto**: Descritas por **Gramáticas Livres de Contexto**, reconhecidas por **Autômatos com Pilha**.
- **Linguagens Sensíveis ao Contexto**: Reconhecidas por **Autômatos Linearmente Limitados**.
- **Linguagens Recursivamente Enumeráveis**: Reconhecidas por **Máquinas de Turing**.

#### Exemplo
A linguagem `{a^n b^n | n ≥ 0}` (mesmo número de `a`s seguido de `b`s) não é regular, mas é livre de contexto.

### 3. Autômatos
- **Autômatos Finitos Determinísticos (AFD)**: Usados para reconhecer linguagens regulares.
- **Autômatos Finitos Não Determinísticos (AFN)**: Permitem múltiplas transições para o mesmo estado.
- **Autômatos com Pilha**: Reconhecem linguagens livres de contexto, usando uma pilha para armazenar informações.
- **Máquinas de Turing**: O modelo mais poderoso, reconhece linguagens recursivamente enumeráveis.

#### Exemplo
Um AFD que reconhece a linguagem `a*b` (zero ou mais `a`s seguidos por um `b`) possui estados que processam repetidamente o símbolo `a` e aceitam a entrada ao encontrar um `b`.

## Formalismos
- **Expressões Regulares**: Descrevem linguagens regulares.
- **Autômatos Finitos**: Reconhecem linguagens regulares.
- **Gramáticas Livres de Contexto**: Descrevem linguagens livres de contexto.
- **Máquinas de Turing**: Podem simular qualquer algoritmo computável.

## Aplicações
- **Validação de entradas** em softwares.
- **Pesquisa de padrões** em ferramentas como `grep`.
- **Compiladores**, para identificação de tokens.

## Recursos Adicionais
- [Hierarquia de Chomsky](https://en.wikipedia.org/wiki/Chomsky_hierarchy)
- [Expressões Regulares](https://en.wikipedia.org/wiki/Regular_expression)
- [Autômatos Finitos](https://en.wikipedia.org/wiki/Finite-state_machine)
