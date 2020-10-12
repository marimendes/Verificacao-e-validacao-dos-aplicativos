## Capacidade de ir e vir
#### Cenário 01

```

Funcionalidade: Acessar conta

Cenário ocorre quando o usuário do sistema deseja iniciar o processo de login
e no meio do processo deseja voltar para a página inicial, optando por não continuar o login.
Neste contexto, o aplicativo apresenta uma mensagem de erro ao usuário.

DADO que o usuário esteja na tela de login
QUANDO preencher o campo de CPF
E clicar no botão voltar
ENTÃO o sistema volta para a tela inicial 
E mostra uma mensagem de erro.


```