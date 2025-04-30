# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Let $G_1 = (V_1, E_1)$ and $G_2 = (V_2, E_2)$, and let both graphs have n nodes and be completely connected.  Since they are completely connected, there is only one way to represent the graph.  For example, a completely connected graph with three nodes can only be represented/drawn as a triangle.  Going back to $G_1$ and $G_2$, since they are completely connected, this means there is an edge between every pair of nodes, allowing for a one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u, v) \in E_1$ iff $(f(u), f(v)) \in E_2$.  A bijection is possible, as there is always a way for a node to be connected to another node no matter the graph.

To prove that a bijection is possible, consider a completely connected graph (f) with four nodes (a, b, c, d), and another completely connected graph (g) with the same four nodes in a different order (c, a, d, b).  This means that a maps to c, b to a, c to b, and d to d, which means a one-to-one and onto function can be defined.  Because every node in a complete graph is connected to every other node, any relabeling of nodes preserves the edge structure.  This shows that a bijection between the vertex sets exists, thus satisfying the condition for isomorphism.  This logic applies to all complete graphs with the same number of nodes.

-----

ChatGPT helped explain the formal definition of isomorphism, which aided me in writing my proof.  Also, Ali helped me understand why completely connected graphs ensure a bijection by drawing out two graphs and showing how the only part of their structure that can change is their label, as they look the same otherwise.  After his explanation, I had a better understanding and was able to add to my proof.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models.  All of the work is my own, except where stated otherwise.  I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
