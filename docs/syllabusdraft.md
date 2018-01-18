Syllabus
--------

##### Introduction


- Calculus review: optimality conditions, gradient, Hessian; + exercises on multivariate differentiation;

- Basic Convex Analysis: definitions; function below its chords; equivalence with other expressions. Subgradients? Construction of lower bounds.


- Convex programs:
	- LPs: bipartite matching, maxflow;
	- Quadratic problems; electrical flow;

- Lagrangian Duality

- Fenchel Duality


- Convex formulations: conic program, SDP cone, eigenvector problem;



##### Algorithms

- First-order-methods: for each algorithm: 2d-pictures, maxflow, Laplacian solvers. see Madry's class.
	- subgradient descent as blueprint;
	- add smoothness;
	- add strong convexity;
	- non-smooth optimization, smoothing;
	- mirror descent and OCO;
	- preconditioning;
	- acceleration;
Structured convex program: quadratic functions and conjugate gradient;

- Coordinate methods: coordinate descent, SGD.

- Solving LPs: choosing the right algorithm;
- General LP solvers: explain assumptions and why they are not there;

- Implicit LPs and separation;
- Cutting-plane methods as a generalization of binary search; equivalence between separation, feasibility, optimization;
 
- Interior-point: conceptual sketch, practical packages, modeling issues; 

- More structured convex programs: LPs flow; Laplacian graphs; positive LPs?

- Practical: different sizes;
- python, numpy;





Interesting Formulations/Equivalences
--------------------------------------
- Circle Packing for planar graphs;
- Entropy optimality formulations;
- 
