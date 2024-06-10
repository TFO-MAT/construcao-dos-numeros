Operações com números naturais:


A adição de dois números naturais, $m$ e $n$, é designada por $m+n$ e definida recursivamente do seguinte modo:
$m+0=m;$
$m+s(n)=s(m+n)$.

A definição acima nos fornece a soma de um número arbitrário $m$ com $0$: $m+0=m$.

Ele nos dá também a soma de $m$ com $s(0)$:

$m+s(0)=s(m+0)=s(m).$

Temos ainda: $m+s(s(0))=s(m+s(0))=s(s(m))$ e assim por diante.

Para cada $m$ natural fixado arbitrariamente, definimos o conjunto $S_m =${$n\in N | m+n$ está definida}. Temos que $0\in S_m$ e se $k\in S_m$, então $s(k)\in S_m$, pois $m+s(k)=s(m+k)$. Logo, por A3, $S_m =\mathbb N$. Como $m$ é arbitrário, $S_m =\mathbb N$, para todo $m\in N$, ou seja, $m+n$ está definida para todo par $(m,n)$ de naturais, o que nos diz que a adição acima definida é de fato uma operação em $\mathbb N$.



Indicaremos por $1$ (lê-se “um”) o número natural que é sucessor de $0$, ou seja, $1=s(0)$.

Proposição: Para todo natural $m$, tem-se $s(m)=m+1$ e $s(m)=1+m$. Portanto, $m+1=1+m$.

Demonstração: para a primeira igualdade, temos: $m+1=m+s(0)=s(m+0)=s(m)$.

Para a segunda igualdade, consideremos o conjunto $A=${$m\in \mathbb N|s(m)=1+m$}. Claramente, $0\in A$, pois $s(0)=1=1+0$. Seja $m\in A$. Vamos mostrar que $s(m)\in A$. De fato, como $s(m)=1+m$, temos que 

$$s(s(m))=s(1+m)=1+s(m),$$

isto é, $s(m)\in A$. Assim, pelo axioma A3, temos $A=\mathbb N$.

Tendo os símbolos $0$ e $1=s(0)$. Definimos:

$s(1)=2$ (lê-se dois);

$s(2)=3$ (lê-se três);

$s(3)=4$ (lê-se quatro);

$s(4)=5$ (lê-se cinco);


e assim por diante. Vemos, então, que $\mathbb N$ contem o conjunto

  

{$0,s(0),s(s(0)),s(s(s(0))),...$}$=${$0,1,2,3,...$}.




Teorema: Sejam $m,n$ e $p$ números naturais arbitrários. São verdadeiras as afirmações:

i) Propriedade associativa da adição: $m+(n+p)=(m+n)+p$.

ii) Propriedade comutativa da adição: $n+m=m+n$.

iii) Lei do cancelamento da adição: $m+p=n+p\Rightarrow m=n$


Multiplicação de números naturais:


Definição: A multiplicação de dois números naturais, $m$ e $n$, é designada por $m\cdot n$ e definida recursivamente do seguinte modo:


$m\cdot 0=0$;

$m\cdot (n+1)=m\cdot n+m$.

  
Como de costume, adotaremos a notação de justaposição para a multiplicação: $m\cdot n=mn$.


Teorema: Para $m, n$ e $p$ naturais arbitrários, valem as proposições abaixo:
 

i) $mn \in \mathbb N$, isto é, a multiplicação é, de fato, uma operação em $\mathbb N$;

ii) existência do elemento neutro multiplicativo: $1\cdot n=n\cdot 1=n$;

iii) distributividade: $m(n+p)=mn+mp$ e $(m+n)p=mp+np$;

iv) associatvidade: $m(np)=(mn)p$;

v) $mn=0\Rightarrow m=0$ ou $n=0$;

vi) comutatividade: $nm=mn$.
