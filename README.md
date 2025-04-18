# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Let $G_1 = (V_1, E_1)$ and $G_2 = (V_2, E_2)$, and let both graphs have n nodes and be completely connected.  Being completely connected, this means there is an edge between every pair of nodes, allowing for a one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u, v) \in E_1$ iff $(f(u), f(v)) \in E_2$.  A bijection is possible, as there is always a way for a node to be connected to another node no matter the graph.  There are no isolated nodes, and a corresponding node can always be found in the other graph.

-----

ChatGPT helped explain the formal definition of isomorphism, which aided me in writing my proof.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models.  All of the work is my own, except where stated otherwise.  I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
