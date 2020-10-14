## Validação facial
#### Cenário 01

```

Funcionalidade: Validação facial

O cenário ocorre ao ralizar validação facial sem CNH.

DADO que o usuário esteja na tela de login
E preencher o campo de CPF
E preencher campo senha
QUANDO clicar no botão avançar
ENTÃO abre a tela de ícones dos serviços públicos disponíveis
E não é possível realizar a validação facial 

```

#### Cenário 02

```
Funcionalidade: Validação facial

O cenário ocorre ao realizar validação facial.

DADO que o usuário esteja na tela de validação facial
E realize os comandos para realizar a prova de vida
QUANDO erra algum comando
ENTÃO todos os testes realizados anteriormente são zerados 
E não é possível finalizar com sucesso o teste de validação facial

```

#### Cenário 03

```
Funcionalidade: Validação facial

O cenário ocorre quando o usuário finaliza a validação facial.

DADO que o usuário esteja na tela de validação facial
E realize todos os comandos de prova de vida
QUANDO finaliza os comandos e o app pede para tirar a foto 
E o usuário move o rosto ultrapassando o limite de espaço da marcação indicada
ENTÃO reinicia novamente os comandos de prova de vida
E não é possível finalizar com sucesso o teste de validação facial

```