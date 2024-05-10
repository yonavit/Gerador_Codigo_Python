## Fluxo Funcional

```mermaid
graph LR
A[Início] --> B{Inserir documento}
B --> |CPF (11 dígitos)| C[Validar CPF]
B --> |CNPJ (14 dígitos)| D[Validar CNPJ]
C --> |Válido| E[Mostrar "CPF válido!"]
C --> |Inválido| F[Mostrar "CPF inválido!"]
D --> |Válido| G[Mostrar "CNPJ válido!"]
D --> |Inválido| H[Mostrar "CNPJ inválido!"]
E --> Z[Fim]
F --> Z
G --> Z
H --> Z
```
