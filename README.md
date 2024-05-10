# Validador de CPF e CNPJ

Este script Python valida CPFs e CNPJs.

## Dependências

Não há dependências externas.

## Uso

1. Execute o script.
2. Digite o CPF ou CNPJ quando solicitado.
3. O script informará se o documento é válido ou inválido.

## Fluxo Funcional

```mermaid
graph LR
A[Início] --> B{Obter Documento}
B --> |CPF| C[Validar CPF]
B --> |CNPJ| D[Validar CNPJ]
C --> E[Resultado]
D --> E
E --> F[Fim]
```

## Exemplos

```
Digite o CPF ou CNPJ: 12345678901
CPF válido

Digite o CPF ou CNPJ: 12345678000199
CNPJ válido
``` 
