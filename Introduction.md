## Optimization

It is important to distingish tractable models from nontractable ones.

We can distingish three classes of problems:
- small-scale problems : having five or fewer unknowns and contraints
- intermediate-scale problems : having about six to a hundred or a thousand variables
- large-scale problems : having perhaps thousands or even millions of variables and constraints

This classification is not entirely rigid, but it reflects at least roughly not only size but the basic differences in approach that accompany different size problems.
As a rough rule, small-scale problems can be solved by hand or by a small computer. Intermediate-scale problems can be solved on a personal computer with general purpose mathematical programming codes. Large-scale problems require sophisticated codes that exploit special structure and usually require large computers.

The most important characteristic of a high-speed computer is its ability to perform repetitive operations efficiently, and in order to exploit this basic characteristic, most algorithms designed to solve large optimization problems are iterative in nature.

The theory of iterative algorithms can be divided into three (somewhat overlapping) aspects. The first is concerned with the creation of the algorithms
themselves. Algorithms are not conceived arbitrarily, but are based on a creative examination of the programming problem, its inherent structure, and the efficiencies
of digital computers. The second aspect is the verification that a given algorithm will in fact generate a sequence that converges to a solution point. This aspect is
referred to as *global convergence analysis*, since it addresses the important question of whether the algorithm, when initiated far from the solution point, will eventually converge to it. The third aspect is referred to as *local convergence analysis* or complexity analysis and is concerned with the rate at which the generated sequence of points converges to the solution.

There are in fact two aspects of convergence rate theory. The first is generally known as *complexity analysis* and focuses on how fast the method converges
overall, distinguishing between polynomial time algorithms and non-polynomial time algorithms. The second aspect provides more detailed analysis of how fast
the method converges in the final stages, and can provide comparisons between different algorithms.
