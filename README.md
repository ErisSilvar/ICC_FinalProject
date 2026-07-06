<div align="center">

# Sistema de Cadastro e Agenda de Funcionários em C

Trabalho prático da disciplica de ICC —> Sistema de linha de comando para cadastro e gerenciamento de funcionários, utilizando matrizes e vetores.

**Devs:** Eris e Thiago

</div>

---

## Descrição

O programa permite cadastrar até 10 funcionários (nome, e-mail e salário) e oferece um menu interativo com as seguintes operações:

1. **Cadastrar Novo Funcionário**
2. **Mostrar Todos os Dados**
3. **Buscar Dados de uma Pessoa Específica**
4. **Mostrar Maior Salário**
5. **Mostrar Média Salarial**
6. **Sair**

## Conceitos aplicados

- Vetores e matrizes paralelos (sem uso de `struct` ou variáveis globais)
- Passagem de matrizes e vetores como parâmetros de função
- Manipulação de strings com a biblioteca `<string.h>` (`strcmp`)
- Estrutura de repetição `do-while` para o menu
- Retorno de valores via `return` para atualizar o contador de cadastros no `main()`

## Estrutura de dados

| Dado      | Tipo                | Tamanho          |
|-----------|---------------------|------------------|
| Nome      | `char[10][50]`      | 10 nomes, 49 caracteres cada |
| E-mail    | `char[10][30]`      | 10 e-mails, 29 caracteres cada |
| Salário   | `float[10]`         | 10 valores |
