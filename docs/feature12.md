## Capacidade de ir e vir
#### Cenário 01

```

Funcionalidade: Login

Cenário ocorre quando o usuário do sistema deseja iniciar o processo de login
e no meio do processo deseja voltar para a página inicial, optando por não continuar o login.
Neste contexto, o aplicativo apresenta uma mensagem de erro ao usuário.

DADO que o usuário esteja na tela de login
QUANDO preencher o campo de CPF
E clicar no botão voltar
ENTÃO o sistema volta para a tela inicial 
E mostra uma mensagem de erro.

```

#### Cenário 02

```

Funcionalidade: Login

Cenário ocorre quando o usuário deseja inserir algum dado ao efetuar login.
A aplicação amplia na área em que será efetuado o preenchimento dos dados e ao finalizar o preenchimento
a interface não volta ao seu aspecto original

DADO que o usuário esteja na tela de login
E clique para preecher um campo de dado
Então a tela será ampliada no campo
E o usuário termine de preencher o campo
ENTÃO a tela permanecerá ampliada ao invés de voltar ao seu aspecto original

```

#### Cenário 03

```

Cénario: Mensagem de erro ao voltar da tela de dúvidas frequentes - ANDROID/IOS

O cenário ocorre após o usuário entrar na tela de dúvidas frequentes e decide voltar para a tela anterior.
Neste contexto, o aplicativo apresenta uma mensagem de erro para o usuário onde na verdade só deveria voltar para a tela anterior.

DADO que o usuário clique em "Entrar com gov.br"
E clique em "dúvidas frequentes" indo para essa tela
ENTÃO o usuário decide voltar para a tela anterior clicando na seta superior no canto direito da tela
E mostra uma mensagem de erro.

```
