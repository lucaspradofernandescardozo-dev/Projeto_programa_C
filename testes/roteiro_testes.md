# Roteiro de Testes

Este documento apresenta os testes planejados para verificar o funcionamento dos módulos de busca e validação do projeto.

## 1. Testes de busca linear

### Busca de jogador por nickname

| Teste | Entrada | Resultado esperado |
|---|---|---|
| Jogador existente | Nickname cadastrado | Retornar a posição do jogador |
| Jogador inexistente | Nickname não cadastrado | Retornar ERRO_NAO_ENCONTRADO |
| Quantidade inválida | Quantidade negativa | Retornar ERRO_INVALIDO |
| Parâmetro nulo | Vetor ou nickname nulo | Retornar ERRO_INVALIDO |

### Busca de equipe por nome

| Teste | Entrada | Resultado esperado |
|---|---|---|
| Equipe existente | Nome cadastrado | Retornar a posição da equipe |
| Equipe inexistente | Nome não cadastrado | Retornar ERRO_NAO_ENCONTRADO |
| Quantidade inválida | Quantidade negativa | Retornar ERRO_INVALIDO |
| Parâmetro nulo | Vetor ou nome nulo | Retornar ERRO_INVALIDO |

## 2. Testes de validação

### Entrada de números inteiros

- Informar um número dentro do intervalo permitido.
- Informar um número menor que o limite mínimo.
- Informar um número maior que o limite máximo.
- Informar letras no lugar de números.
- Informar o campo vazio.

### Entrada de textos

- Informar um texto válido.
- Informar um campo vazio.
- Informar apenas espaços.
- Informar um texto maior que o limite permitido.

## 3. Observação

Os casos descritos representam o planejamento dos testes. Os resultados deverão ser registrados após a execução das funções e a integração dos módulos do projeto.
