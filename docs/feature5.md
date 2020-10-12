## Forçar falhas nos campos de input
#### Cenário 01

``` 
Funcionalidade: Progamas existentes

O cenário ocorre quando o usuário acessa aos programas existentes no aplicativo. 
Ao realizar o login com CPF (mesmo não possuindo CNH) o usuário é
encaminhado diretamente à página de validação facial, mas não reconhece o
rosto do usuário, não avançando e não tendo opção de entrar na página de
programas existentes.

DADO que eu clico em “Entrar com gov.br”, mesmo não tenho CNH
QUANDO acesso a página dos serviços públicos digitais
Então sou levada para validação facial
E após o programa de validação não me reconhecer, não sou redirecionado para
a tela dos programas existentes.

```

#### Cenário 02

``` 
Funcionalidade: Validação facial

O cenário ocorre quando o usuário acessa a página de login e consegue acessar com sucesso a
plataforma em que estão disponíveis os serviços públicos, como o INSS,
certificado digital entre outros, mas não é possível acessá-los. Aparece somente um
ícone com a imagem da logo do serviço e quando tentamos acessar um serviço
em específico, o usuário é redirecionado para uma página em branco, não
informando se ocorreu algum erro. Este problema ocorre com todos os serviços
desde que o usuário possua validação facial.

DADO que eu desejo ter acesso aos programas disponibilizados pelo app
E informo CPF e senha
E faço a validação facial
QUANDO acesso a página com os programas disponíveis
ENTÃO aparece os ícones dos serviços públicos digitais
QUANDO tento acessar um serviço em específico clicando no ícone,
ENTÃO sou redirecionado para uma página em branco, não informando se
ocorreu algum erro e não avança.


```
