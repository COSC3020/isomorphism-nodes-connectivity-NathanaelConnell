# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

If two grpahs A and B have the same number of nodes and are completely connected, they must be isomorphic becuase their structure is entirely determined by the number of nodes. A completely connected grpah has an edge between every pair of distinct vertices. Since A and B have the same number of nodes we can construct a bijection f from the vertices of A to the vertices of B. This bijection ensures that every edge (u,v) in A maps to a corresponding edge (f(u), f(v)) in B and vice versa preserving adjacecy. The two grpahs are structurally identical and the existence of this bijection demonstates that A and B are isomorphic.

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."
