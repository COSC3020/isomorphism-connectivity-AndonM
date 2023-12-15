[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11974289&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do \emph{not} have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Consider two completely connected graphs, A and B, that contain the same number of nodes. Let $G_1 = (V_1, E_1)$ for A and $G_2 = (V_2, E_2)$ for B. Our bijective function may then be defined as follows:  

$f: A <=> B$  

$V{{_A}_1} <=> V{{_{B}_1}$  
$V{{_A}_2} <=> V{{_B}_2}$   
$V{{_A}_3} <=> V{{_B}_3}$   

.....  

$V{{_A}_n} <=> V{{_B}_n}$  

From this finding we can then say that for any edge (u, v) $\in E_1, \exists (f(u), f(v)) \in E_2$. This ensures isomorphism. (at least in the forward direction) Going the other way now we see that...  

For any edge (c, d) $\in E_2, \exists (f^{-1}(c), f^{-1}(d)) \in E_2,$ where $f^{-1}$ is the inverse bijection of f. This ensures isomorphism in the reverse direction.  

We have shown that any graphs completely connected graphs, A and B, with the same number of nodes must be isomorphic as there exists a bijective function $f: V_1 \rightarraow V_2$ such that $(u, v) \in E_1$ iff $(f(u), f(v)) \in E_2$
