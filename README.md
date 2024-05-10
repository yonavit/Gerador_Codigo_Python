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
