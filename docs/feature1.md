## Capacidade de ir e vir
#### Cenário 01

``` 
Funcionalidade: Capacidade de ir e vir

O cenário ocorre quando o usuário avança para uma tela, mas decide retornar a tela anterior.

DADO que eu esteja na tela de login do aplicativo
E clico no botão "Entrar com Gov.br"
QUANDO eu avanço pra próxima tela
E decido voltar clicando na seta no canto superior esquerdo
ENTÃO eu volto pra tela inicial, mas aparece uma mensagem de erro.


```

#### Cenário 02

``` 
Funcionalidade: Capacidade de ir e vir

O cenário ocorre quando o usuário avança para uma tela, preenche os seus dados, mas decide retornar a tela anterior.

DADO que eu esteja na tela de login do aplicativo
E clico no botão "Entrar com Gov.br"
QUANDO eu avanço pra próxima tela
E preencho os meus dados no campo de CPF e senha
E decido voltar clicando na seta no canto superior esquerdo
ENTÃO eu volto pra tela inicial, mas aparece uma mensagem de erro.


```

