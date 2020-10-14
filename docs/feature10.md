## Recuperar senha
#### Cenário 01

```
Funcionalidade: Recuperar senha

Esse cenário ocorre ao realizar alteração de senha via Validação Facial.
OBS: A validação facial para recuperação de senha está sendo muito longa. Mais de 15 comandos.

DADO que o usuário deseja realizar login mas não lembra sua senha cadastrada
QUANDO o usuário digitar o CPF
E no campo de senha, clicar em "esqueci minha senha"
ENTÃO o usuário vê as opções para recuperação de senha
QUANDO o usuário escolhe Validação Facial
ENTAO inicia-se o processo de prova de vida
E apesar de seguir todos os comandos apresentados, o usuário não consegue concluir a prova de vida

```
#### Cenário 02

```
Funcionalidade: Recuperar senha

Esse cenário ocorre ao realizar alteração de senha a partir da conta do Banco do Brasil.

O processo de alteração de senha têm gerado muitas dúvidas por parte dos usuários. 
Imagino que o fluxo via BB pode gerar confusão, já que o usuário precisa buscar o 
código dentro do app do BB,
em locais não muito comuns para um usuário médio.

DADO que o usuário deseja realizar login mas não lembra sua senha cadastrada
Quando o usuário digitar o CPF
E no campo de senha, clicar em "esqueci minha senha"
ENTÃO o usuário vê as opções para recuperação de senha
QUANDO o usuário escolhe recuperação via Banco do Brasil
ENTAO são requisitadas informações da conta bancária do BB (Conta, Agencia e senha)
E ao incluir todas as informações, o aplicativo do BB informa que recebeu um código de acesso mas não apresenta o código.
Então o usuário precisa abrir o banco do brasil, ir em Conta e verificar a parte de Mensagens do APP
E ao incluir o código no campo requisitado, observamos uma falha na validação
E o usuário não consegue concluir o fluxo de recuperação de senha.

```
#### Cenário 03

```

Dado que o usuário segue o  fluxo de recuperação de senha algumas vezes.
Não sabemos se este problema está diretamente ligado ao fluxo de recuperação de senha,
mas após realizar esse fluxo algumas vezes, observou-se que o aplicativo ficou travado na tela de abertura.
Mesmo após fechar e abrir o app algumas vezes, o app segue travado na página de abertura. 
A solução só surgiu ao desinstalar e instalar o app na versão anterior. Provavelmente isso ocorre devido a uma instabilidade
no ambiente de homologação.

DADO que o usuário faça mais de 2 recuperações de senha seguidas
QUANDO o usuário deseja abrir novamente o APP
ENTAO o app fica preso na tela de apresentação inicial de abertura do APP
E a unica opção por parte do usuário é fechar o APP
E para solucionar, o usuário precisou desinstalar e instalar a versão anterior

```