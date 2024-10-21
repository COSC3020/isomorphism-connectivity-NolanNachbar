# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Consider a theorem that says if two graphs $A$ and $B$ are isomorphic, they *do* have to
be completely connected. 

Now consider two graphs:
Graph $A$ which has vertices $V = \{1,2,3,4\}$ and edges $E = \{ (1,2), (2,3), (3,4)\}$.
Graph $B$ which has vertices $V = \{a,b,c,d\}$ and edges $E = \{ (a,b), (b,c), (e,f)\}$.

These graphs are not completely connected because edges like $(1,4)$ or $(a, f)$ do not exist. 

Yet, it can be shown that these graphs are isomorphic. For example, look at the mapping of the one-to-one and onto function (bijection) that takes:
$$
1 \to a\\
2 \to b\\
3 \to c\\
4 \to d
$$

Thus the graphs are isomorphic, but they are not completely connected; this is clearly a contradiction to the theorem. Thus, if two graphs $A$ and $B$ are isomorphic, they *do not* have to
be completely connected.

I certify that I have listed all sources used to complete this exercise, including the use of any large language models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice. 

I did this all independently except for the slides.
