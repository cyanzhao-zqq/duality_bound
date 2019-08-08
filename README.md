# duality bound for nanophotonic bound problem

Lagrange duality has been a powerful technique in convex optimization community. In nanophotonic community, we have lots of bound problems that can be turned into an optimization problem. We want to leverage the powerful Lagrange duality method to solve those bound problems that we are interested in.

The main idea of Lagrange duality is the minmax inequality: minmax L(x,y) <= maxmin L(x,y)

This inequality will always hold and we can always write down the dual 'mathematically', i.e. maxmin L. However, in order to use this to solve for a meaningful bound, we need to write down analytical form of 'minL' first. It is proven that minL will be a function with nice property (concavity/convexity) independent of the property of L, which is a great thing. But often, we cannot write down the analytical form of minL, which make the implementation of this approach difficult. 

In this paper, they proposed a great mathematic formulation that allows us to write down the lagrangian duality. However, physical-wise, this formulation may not be that useful. We gain inspiration from their work and want to extend it further.

