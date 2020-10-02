## Experiência do Usuário
#### Cenário 01

``` 
Funcionalidade: Tutorial da tela de reconhecimento facial

O cenário ocorre quando o usuário deseja fazer o reconhecimento facial e é levado para o tutorial. Porém, não tem nenhuma seta na página indicando para o usuário que ele deve arrastar pra o lado para prosseguir.

DADO que eu esteja na tela de reconhecimento facial
E clique em prosseguir
QUANDO eu avanço para o tutorial do reconhecimento facial
E decido ir pra próxima página ou voltar pra tela inicial 
ENTÃO eu permaneço na mesma página, pois não tem nenhuma seta ou botão me informando como prosseguir ou como voltar


```

#### Cenário 02

``` 
Funcionalidade: Reconhecimento facial

O cenário ocorre quando o usuário está realizando o reconhecimento facial, porém ao enviar a foto a qualidade da imagem é reduzida e a validação falha.

DADO que eu entre na etapa de validação facial
E realize o procedimento de Prova de Vida em um ambiente bem iluminado
E a imagem apresentada possui boa qualidade
QUANDO ocorre a captura automática da imagem
E a validação passa para fase de enviar a imagem
ENTÃO a qualidade da imagem é reduzida drasticamente
E ocorre erro na validação facial.


```

#### Cenário 03

``` 
Funcionalidade: Termos de Uso

O cenário ocorre quando o usuário está na tela de termos de uso e aparece a sigla "LGPD", mas não é informado para o usuário o significado dessa sigla.

DADO que eu esteja na tela de termos de uso do aplicativo
E me deparo com a sigla "LGPD"
ENTÃO eu recuso os termos de uso, pois não sei o que essa sigla significa.

```


#### Cenário 04

``` 
Funcionalidade: Validação facial

O cenário ocorre quando o usuário, que não tem CNH, tenta fazer o acesso ao aplicativo utilizando a validação facial e não consegue. 

Não há nenhuma mensagem no aplicativo informando que esse meio de entrada só funciona pra quem tem CNH.

DADO que eu esteja na tenha CNH 
E tente realizar o meu login por meio da validação facial
ENTÃO eu o sistema aparece uma mensagem de erro informando que eu não tenho cadastro


```