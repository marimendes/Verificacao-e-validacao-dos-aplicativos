## Erro comportamental
#### Cenário 01

```

Funcionalidade: Leitura dos Termos de uso ao criar conta.

Cenário ocorre quando o usuário deseja ler os Termos de uso ao tentar criar sua
conta.

DADO que o usuário esteja na tela de login
E clique no botão "Crie sua conta"
E clique em "Validação Facial no App Meu gov.br"
E clique em "Termos de uso"
E clique em "Fechar"
ENTÃO é apresentado um popup erro "Sistema de origem desconhecido".

```
#### Cenário 02

```

Funcionalidade: Dúvidas frenquentes

Cenário ocorre quando o usuário deseja acessar a página de dúvidas frequentes, 
mas a página está fora do ar.

DADO que o usuário esteja na tela de login
E clique no botão "Dúvidas Frequentes"
ENTÃO o usuário é levado pra próxima tela e aparace a mensagem "Página da Web não disponível"


```