## Capacidade de ir e vir
#### Cenário 01

``` 
Funcionalidade: Acessar aplicativo

O cenário ocorre quando o usuário avança para uma tela, mas decide retornar a tela anterior.

DADO que eu esteja na tela de login do aplicativo
E clico no botão "Entrar com Gov.br"
QUANDO eu avanço pra próxima tela
E decido voltar clicando na seta no canto superior esquerdo
ENTÃO eu volto pra tela inicial, mas aparece uma mensagem de erro.


```

#### Cenário 02

``` 
Funcionalidade: Acessar conta

O cenário ocorre quando o usuário avança para uma tela, preenche os seus dados, mas decide retornar a tela anterior.

DADO que eu esteja na tela de login do aplicativo
E clico no botão "Entrar com Gov.br"
QUANDO eu avanço pra próxima tela
E preencho os meus dados no campo de CPF e senha
E decido voltar clicando na seta no canto superior esquerdo
ENTÃO eu volto pra tela inicial, mas aparece uma mensagem de erro.


```

####  Cenário 03

```
Funcionalidade: Criar conta

O cenário ocorre quando o usuário decide criar a sua conta usando a opção do Bando do Brasil.
Porém um erro ocorre no meio do processo de criação e o usuário não consegue prosseguir.

DADO que eu clico em “Entrar com gov.br”
QUANDO clico em “Crie sua conta”
E escolho a opção “Banco do Brasil”
E autorizo os termos de uso
E preencho os meus dados da conta do Banco do Brasil
E preencho com o código de autorização que eu recebi
ENTÃO eu sou informada que já tenho uma conta no Meu Gov.br,
mas continuo na tela de cadastro
E ao tentar prosseguir preenchendo o meu nome, aparece uma
mensagem de erro.
E eu não consigo nem avançar ou voltar para outra tela.
```
