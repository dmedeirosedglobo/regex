# Repositório de Regex - Expressões Regulares

# Índice
- [Validar Datas](#datas) 

## Datas
* ``Datas no formato dd/mm/20aa``

>Valida datas a partir do ano 2000 separado por "/"
```
^(([0][1-9]|[12][\d])[\/]([0][2])[\/]([2][0][\d]{2}))$|^(([0][1-9]|[12][\d]|[3][0])[\/]([0][469]|[1][1])[\/]([2][0][\d]{2}))$|^(([0][1-9]|[12][\d]|[3][1])[\/]([0][13578]|[1][02])[\/]([2][0][\d]{2}))$
```
