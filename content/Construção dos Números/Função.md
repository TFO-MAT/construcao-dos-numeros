Função é uma [[Relação]] que é estabelecida entre dois conjuntos em que há uma correspondência entre os elementos de um certo [[Conjunto]] $A$ com elementos de um conjunto $B$.

Uma função $f:A\to B$ consta de três partes: um conjunto $A$, chamado “domínio” da função (ou o conjunto onde a função é definida), um conjunto $B$, chamado “contradomínio” da função (ou o conjunto onde a função toma valores), e uma regra que permite associar, de modo bem determinado, a cada elemento $x\in A$, um único elemento $f(x)\in B$, chamado o “valor” que a função assume em $x$ (ou no ponto $x$).

Usa-se a notação $x\mapsto f(x)$ para indicar que $f$ faz corresponder a $x$ o valor $f(x)$.
Muitas vezes se diz a “função $f$” em vez de “a função $f:A\to B$”. Neste caso, ficam subentendidos o conjunto $A$, domínio de $f$, e o conjunto $B$, contradomínio de $f$.
Não se deve confundir $f$ com $f(x)$ : $f$ é a função, enquanto que $f(x)$ é o valor que a função assume num ponto $x$ do seu domínio.
A natureza da regra que ensina como obter o valor $f(x)\in B$ quando é dado $x\to A$ é inteiramente arbitrária, sendo sujeita apenas a duas condições:

1ª) Não deve haver exceções: a fim de que $f$ tenha o conjunto $A$ como domínio, a regra deve fornecer $f(x)$ para todo $x\in A$;

2ª) Não deve haver ambiguidades: a cada $x\in A$, a regra deve fazer corresponder um único $f(x)$ em $B$.

Vemos que não existem funções “plurivocas”. Pela segunda condição, acima, se $x=y$ em $A$, então, $f(x)=f(y)$ em $B$.
Segue-se das considerações acima que duas funções $f:A\to B$ e $g:A'\to B'$ são iguais se, e somente se, $A=A'$, $B=B'$ e $f(x)=g(x)$ para todo $x\in A$. Ou seja, duas funções são iguais quando têm o mesmo domínio, o mesmo contradomínio e a mesma regra de correspondência.


Injetividade : Uma função $f:A\to B$ chama-se injetiva (ou biunívoca) quando, dados $x, y$ quaisquer em $A$, $f(x)=f(y)$ implica $x=y$. Em outras palavras: quando $x\neq y$, em $A$, implica $f(x)\neq f(y)$, em $B$. ^7a0c04

Sobrejetividade : Uma função $f:A\to B$ chama-se sobrejetiva (ou sobre $B$) quando, para todo $y\in B$ existe pelo menos um $x\in A$ tal que $f(x)=y$.

Bijetividade : Uma função $f:A\to B$ chama-se bijetiva (uma bijeção, ou uma correspondência biunívoca) quando é injetiva e sobrejetiva ao mesmo tempo.