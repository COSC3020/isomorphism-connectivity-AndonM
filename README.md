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

Assume that two graphs A and B are isomorphic. Further assume that they must be completey connected. Since A & B are both isomorphic, there exists a bijective function that ensures an adjacency relationship between the nodes of both graphs. Consider the case in which A is a complete graph with n nodes (K_{n}) and B is also a complete graph with p nodes, (K_{p}) where n \neq p. Under the asssumption, A and B are isomorphic. Therefore, there must exist a one-to-one correspondence between their nodes. However, we have n nodes in A and p nodes in B where n \neq p. If we have n nodes in A and m nodes in B, and the two are not equal, then it is impossible to find a binective function mapping the nodes of A to the nodes of B while preserving the adjacency relationship. This is because in a complete graph, each node must be connected to every other node: in a situation in which one graph has more nodes than the other, there is bound to be a node(s) in one graph with more connections than the corresponding node(s) in the other. This contradiction arises from the assumption that A and B must be completely connected if they are isomorphic. therefore, graphs A and B need not be completely connected to be isomorphic.
