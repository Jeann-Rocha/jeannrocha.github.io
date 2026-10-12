# Lista 4 — Topologia

**Referência:** Lista 4  
**Tópicos:** métricas, espaços completos, compacidade, continuidade, separabilidade  

---

## Exercícios

- **1.** Sejam $a,b\in\mathbb{R}$, $a<b$, e $R([a,b])$ o conjunto das funções integráveis segundo Riemann de $[a,b]$ em $\mathbb{R}$. Definindo
  $$
  d_1:R([a,b])\times R([a,b])\to\mathbb{R}_+,\quad
  (f,g)\mapsto \int_a^b |f(x)-g(x)|\,dx,
  $$
  mostre que $d_1$ é uma pseudométrica.

- **2.** Considere $(C([a,b];\mathbb{R}))\subset B([a,b];\mathbb{R})$ com a norma do sup.
  - i) Mostre que $\operatorname{int}(C([a,b]))=\varnothing$.
  - ii) Mostre que $\overline{C([a,b])}=C([a,b])$.
  - iii) O conjunto $D$ das funções descontínuas em $[a,b]$ é denso em $B([a,b])$.

- **3.** Sejam $K_1$ e $K_2$ subconjuntos compactos disjuntos de um espaço de Hausdorff $X$. Demonstre que existem abertos $Q_1,Q_2$ disjuntos tais que $K_1\subset Q_1$ e $K_2\subset Q_2$.

- **4.** Seja $A\subset X$, com $X$ espaço topológico. Um conjunto $\mathcal{J}$ de vizinhanças de $A$ é um sistema fundamental de vizinhanças de $A$ se toda vizinhança de $A$ contém um $V\in\mathcal{J}$. Demonstre que, num espaço métrico, todo subconjunto compacto tem um sistema fundamental enumerável de vizinhanças.

- **5.** Seja $M$ um espaço métrico completo e
  $$
  A_1\supset A_2\supset \cdots \supset A_n\supset A_{n+1}\supset\cdots
  $$
  uma sequência de subconjuntos fechados não vazios de $M$ com
  $$
  \lim_{n\to\infty}\operatorname{diam} A_n=0.
  $$
  Mostre que $\bigcap_n A_n$ é um único ponto $x_0$.

- **6.** Um espaço topológico é dito separável se contém um subconjunto enumerável denso. Diz-se que um espaço topológico $X$ satisfaz o primeiro axioma de enumerabilidade se todo ponto $x\in X$ tem um sistema fundamental enumerável de vizinhanças. Seja $X$ um espaço topológico que tem uma base enumerável $\mathcal{B}$. Mostre que $X$ é separável e satisfaz o primeiro axioma de enumerabilidade.

- **7.** Um espaço métrico é separável se, e somente se, tem uma base enumerável de abertos.

- **8.** Seja $(M,d)$ um espaço métrico. Demonstre que
  $$
  d^*(x,y)=\min\{d(x,y),1\}
  $$
  é limitada sobre $M$ e que é uniformemente equivalente à distância $d$.

- **9.** Seja $F$ um espaço de Hausdorff. Um subconjunto $A\subset F$ é dito relativamente compacto se seu fecho $\overline{A}$ for compacto. Seja $A\subset M$ relativamente compacto, com $M$ espaço métrico. Mostre que $A$ é limitado.

- **10.** Demonstre que toda aplicação biunívoca contínua de um espaço compacto sobre um espaço de Hausdorff é um homeomorfismo.

- **11.** Seja $M$ um espaço métrico. Considere $M\times M$ com a topologia produto e
  $$
  f:M\times M\to\mathbb{R},\quad f(x,y)=d(x,y).
  $$
  Mostre que $f$ é contínua.

- **12.** A aplicação $x\in\mathbb{R}\mapsto |x|$ é uniformemente contínua. Verifique!

- **13.** Seja $F:\mathcal{C}([a,b])\to\mathbb{R}$,
  $$
  F(f)=\int_a^b f(x)\,dx.
  $$
  Mostre que $F$ é contínua.

- **14.** Demonstre que a aplicação $F:\mathcal{C}([a,b])\to\mathcal{C}([a,b])$ dada por
  $$
  F(x)(t)=\int_a^t x(s)\,ds,\quad a\le t\le b,
  $$
  é contínua.

- **15.** Existe uma única função $y\in\mathcal{C}([0,1],[-1,1])$ que satisfaz
  $$
  4y(t)+\operatorname{sen} y(t)+\int_0^t [1+y^2(s)]\operatorname{sen} s\,ds=0,
  \quad y(0)=0.
  $$