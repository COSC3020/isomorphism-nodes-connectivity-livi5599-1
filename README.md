# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

-----

Let $G_1 = (V_1, E_1)$ and $G_2 = (V_2, E_2)$, and let both graphs have v vertices and be completely connected.  Being completely connected, every distinct vertex is connected to every other vertex by an edge e.  Since they are completely connected, their structure is unique, as there is only one way for vertices to be connected with every other vertex.

Based on the fact that both graphs have the same number of vertices, there exists a one-to-one and onto function $f: V_1 \rightarrow V_2$ such that vertices $(u, v) \in E_1$ iff $(f(u), f(v)) \in E_2$.  This function is a bijection, because every vertex in $V_1$ can be assigned to a unique vertex in $V_2$ with no vertices left over, and vice versa.  This is possible because both graphs have the same number of vertices and the same edge pattern.

The function f above needs to be a bijection so every node in $G_1$ is mapped to a single node in $G_2$, and vice versa.  This preserves the structure of the graphs.  The bijection function exists because the only difference between completely connected graphs is their node labels, as their structures are the same. 

If vertices $(u, v)$ in $G_1$ are connected, then their images under the bijection $(f(u), f(v))$ must be connected in the other graph.  This is because of the fact that every pair is connected in both graphs, which means the edge set in each graph includes all possible edges, meaning every vertex is connected to every other vertex in each graph.

Because this function f preserves edges and is a bijection, as shown above, the two graphs G1 and G2 are isomorphic by definition.  This applies to all graphs that have the same number of vertices and are completely connected.

-----

ChatGPT helped explain the formal definition of isomorphism, which aided me in writing my proof.  Also, Ali helped me understand why completely connected graphs ensure a bijection by drawing out two graphs and showing how the only part of their structure that can change is their label, as they look the same otherwise.  After his explanation, I had a better understanding and was able to add to my proof.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models.  All of the work is my own, except where stated otherwise.  I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
