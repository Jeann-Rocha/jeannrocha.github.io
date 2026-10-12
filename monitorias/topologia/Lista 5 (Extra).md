# Lista 5 (Extra) — Topologia

**Referência:** Lista 5 Extra  
**Tópicos:** interior, fronteira, quocientes, conexidade, compacidade, separabilidade  

---

## Exercícios

- **1.** Dado $X$ um espaço topológico e $A\subset X$, prove que
  $$
  X=A^\circ\cup \partial A\cup (X\setminus A)^\circ.
  $$
  Conclua que
  $$
  \overline{X\setminus A}=X\setminus A^\circ,\quad
  (X\setminus A)^\circ=X\setminus \overline{A},\quad
  \partial(X\setminus A)=\partial A.
  $$
  Prove que a função característica $\chi_A:X\to\mathbb{R}$ é contínua em $x$ se, e somente se, $x\notin\partial A$.

- **2.** Caracterizar o espaço quociente $\mathbb{R}^2/\sim$ em cada um dos seguintes casos:
  - a) $(x_0,y_0)\sim(x_1,y_1)\iff x_0+y_0^2=x_1+y_1^2$
  - b) $(x_0,y_0)\sim(x_1,y_1)\iff x_0^2+y_0^2=x_1^2+y_1^2$
  - c) $(x_0,y_0)\sim(x_1,y_1)\iff x_0-x_1\in\mathbb{Z}\text{ e }y_0=(-1)^{x_0-x_1}y_1$
  - d) $(x_0,y_0)\sim(x_1,y_1)\iff x_0-x_1\in\mathbb{Q}\text{ e }y_0-y_1\in\mathbb{Q}$

- **3.** Seja $\{X_i\}_{i\in I}$ uma família de espaços topológicos conexos. Prove que $X=\prod_{i\in I}X_i$, com a topologia produto, é conexo.

- **4.** Prove que o conjunto $A=\{1/n:n\in\mathbb{N}\}\subset\mathbb{R}$ não é compacto.

- **5.** Lema do tubo: Seja $K$ compacto, $x\in X$, e $U\subset K\times X$ aberto tal que $K\times\{x\}\subset U$. Prove que existe $V\subset X$ aberto, com $x\in V$, tal que $K\times V\subset U$.

- **6.** Seja $X$ um espaço $T_2$ (Hausdorff).
  - (a) Prove que se $K$ é compacto e $f:K\to X$ é contínua, então $f$ é fechada.
  - (b) Prove que se $A,B\subset X$ são compactos disjuntos, então podem ser separados por abertos disjuntos de $X$.

- **7.** Prove que $X=\prod_i X_i$ é Hausdorff se, e somente se, cada $X_i$ é.

- **8.** Prove que se para cada $n\in\mathbb{N}$ o espaço $X_n$ admite um subconjunto denso enumerável, então $\prod_n X_n$ também admite.

- **9.** Seja $(f_n)$ uma sequência de Cauchy em $\mathcal{C}[0,1]$ tal que $f_n(x)\to f(x)$ para todo $x\in[0,1]$. Então $(f_n)$ converge para $f$ uniformemente.

- **10.** Demonstre que $C^*(\mathbb{R},\mathbb{C})$, o conjunto de todas as funções contínuas e limitadas de $\mathbb{R}$ em $\mathbb{C}$, não é separável.  
  Sugestão: Considere $e_\alpha(t)=e^{i\alpha t}$ e $d(e_\alpha,e_\mu)=2$, para todo $\alpha\ne\mu$.