## Experiência do Usuário
#### Cenário 01

```

Funcionalidade: Notificação

Cenário ocorre quando o usuário do sistema realiza o login no aplicativo.
Ao se conectar e ir para a tela de notificação o usuário deve receber uma série de 
mensagens de autorização.

DADO que o usuário esteja na tela de login
QUANDO preencher o campo de CPF
E a senha
ENTÃO o usuário faz o login ao aplicativo
E vai para a tela de notificações, não encontrando nenhuma mensagem


```
#### Cenário 02

```

Funcionalidade: Listagem de serviços públicos

Este cenário ocorre na situação em que o usuário não possui CNH e não consegue realizar a validação facial. 
Após realizar essa tentativa, o usuário se encontra em uma página de listagem de serviços públicos. 
Ao encontrar esta página, o usuário
não consegue sair mais, ficando preso na página.

CONTEXTO: Dado que o usuário não possua CNH e e não consiga realizar a validação facial.

DADO que o usuário esteja na tela de ícones dos serviços públicos disponíveis (após tentar realizar a validação)
E deseja voltar usando a tecla voltar do celular 
E clique na tecla voltar repetidas vezes
ENTÃO o usuário permanece na tela de ícones de serviços 
E não é possível sair da tela de ícones


```

#### Cenário 03 

```

Funcionalidade: Recuperação de senha 

Este cenário ocorre quando o usuário solicita a opção de "esqueci minha senha". 
Após clicar nessa opção, o usuário é levado pra tela onde escolhe como irá recuperar a sua senha. 
Os icones dessa tela estão todos desalinhados. 

DADO que o usuário esteja na tela de login
E preencha o CPF avançando pra próxima tela
E clique em "esqueci minha senha"
ENTÃO aparecem as opções para o usuário escolher como recuperar a senha
E os icones estão desalinhados.

```

#### Cenário 04 

```

Funcionalidade: Ler o QR CODE 

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

#### Cenário 05 

```

Funcionalidade: Tela de informações (FAQ)

No cenário em que o usuário deseja ter mais informações sobre o app e, clica no " O que é o Meu gov.br", 
o mesmo não encontra informações relevantes sobre a funcionalidade e usabilidade do app.

DADO que o usuário deseja ter informações sobre o App
E clica em " O que é o Meu gov.br " que se encontra no Menu
ENTÃO aparecem informações
MAS as informações não são suficientes para que o usuário possa saber como o app funcionae o que ele poderá encontrar em seu acesso

```