## Validação Facial
#### Cenário 01

```

Funcionalidade: Validação facial

Este cenário ocorre quando o usuário realiza a validação fácil, 
em um ambiente claro e com o possuindo CNH mas não obtem exito.

DADO que o usuário esteja na tela de validação facial
E realize todos os comandos de prova de vida em um ambiente claro e uma camera boa
QUANDO finaliza a validação fácial
ENTÃO o sistema fala que não foi possível encontrar os dados do usuário na biometria

```