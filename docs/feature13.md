
## Experiência do Usuário
#### Cenário 01

```

Funcionalidade: Recuperar senha

Este cenário ocorre quando o usuário solicita a opção de "esqueci minha senha". 
Após clicar nessa opção, o usuário é levado pra tela onde escolhe como irá recuperar a sua senha. 
Os icones dessa tela estão todos desalinhados. 

DADO que o usuário esteja na tela de login
E preencha o CPF avançando pra próxima tela
E clique em "esqueci minha senha"
ENTÃO aparecem as opções para o usuário escolher como recuperar a senha
E os icones estão desalinhados.

```

#### Cenário 02

```

Funcionalidade: Ler QR code

Este cenário ocorre quando o usuário solicita a opção de "ler o QR code" na tela inicial.
Após passar pelo tutorial e clicar em "ler o QR code", o usuário é levado para a tela onde o irá ler o QR code.
Ao clicar em cancelar, o usuário é levado para uma tela de erro.

DADO que o usuário esteja na tela inicial
E escolha a opção "Ler QR code"
E passa pelo tutorial
E clique no botão "Ler QR code"
ENTÃO a camera é habilitada para que o usuário possa ler o QR code
MAS o usuário seleciona a opção de "cancelar" 
E é levado para uma tela de erro ao invés de apenas voltar para a tela inicial

```

#### Cenário 03

```

Funcionalidade: FAQ

No cenário em que o usuário deseja ter mais informações sobre o app e, clica no " O que é o Meu gov.br", 
o mesmo não encontra informações relevantes sobre a funcionalidade e usabilidade do app.

DADO que o usuário deseja ter informações sobre o App
E clica em " O que é o Meu gov.br " que se encontra no Menu
ENTÃO aparecem informações 
MAS as informações não são suficientes para que o usuário possa saber como o app funciona 
E o que ele poderá encontrar em seu acesso


```

#### Cenário 04

```

Funcionalidade: Notificações e Autorizações

Este cenário ocorre quando o usuário faz login no aplicativo e solicita a opção de "Notificaçãoes" 
e logo em seguida clica em "Autorizações"
Após isso o usuário é levado para a tela de Autorizações e aparece uma mensagem informando 
"Você não possui pedidos de autorização!", mas não explica o que são essas autorizações.

DADO que o usuário faça login no aplicativo Meu Gov.br
E clica no botão de "Notificações"
E seleciona a opção de "Autorizações"
ENTÃO o usuário vai pra uma tela de autorizações


```

#### Cenário 05

```

Funcionalidade: Validação facial

Cenário ocorre quando o usuário deseja recuperar sua senha pelo método de validação facial.
Após fazer a Validação Facial, a tela com o campo para preencher a emissão da CNH tem seu botão
"voltar" sem função ao clicar.

DADO que o usuário esteja na tela de login
E preencha o CPF avançando pra próxima tela
E clique em "esqueci minha senha"
ENTÃO aparecem as opções para o usuário escolher como recuperar a senha
E ele selecione o método "Validação Facial no aplicativo Meu gov.br"
E verifique o Captcha
E passe pelo tutorial
E realize a validação facial
E clique em "Voltar"
ENTÃO nada acontece.



```

#### Cenário 06

```

Funcionalidade: Validação facial

Cenário ocorre quando o usuário deseja recuperar sua senha pelo método de validação facial.
Após fazer a Validação Facial e preencher a última emissão da CNH, caso o usuário aperte em "voltar"
a aplicação irá retornar para uma página em branco.

DADO que o usuário esteja na tela de login
E preencha o CPF avançando pra próxima tela
E clique em "esqueci minha senha"
ENTÃO aparecem as opções para o usuário escolher como recuperar a senha
E ele selecione o método "Validação Facial no aplicativo Meu gov.br"
E verifique o Captcha
E passe pelo tutorial
E realize a validação facial
E preencha a data da última emissão de sua CNH
E clique em "Voltar"
ENTÃO a aplicação irá retornar para uma página em branco

```

