# Computational-Calculus
This project explores calculus through computation, bridging mathematical theory and modern automatic differentiation frameworks (PyTorch and JAX).
It systematically implements:

Basic Differentiation: Single-variable derivatives using autograd.

Vectorized Derivatives: Efficient computation for multiple points using torch.autograd.grad and jax.vmap.

Parametric Equations: Derivatives of functions with respect to time, computing dy/dx for x(t) and y(t).

Implicit Differentiation: Solving F(x, y) = 0 numerically and computing dy/dx automatically.

Integration-Ready Workflow: Structured QA-style checklists for gradient computation, ensuring reproducibility and clarity.

Key Features:

Fully worked PyTorch and JAX implementations.

Step-by-step checklists and QA guides for gradient-based computation.

Demonstrates numerical solution integration for implicit functions.

Designed for learners, researchers, and engineers to explore computational calculus interactively.

Technical Skills Showcased:

PyTorch (autograd, vectorized gradients)

JAX (grad, vmap, vectorized differentiation)

Numerical root-finding (scipy.optimize.fsolve)

Parametric and implicit differentiation

Systematic QA-driven workflow

Use Cases / Applications:

Physics, engineering, and AI simulations requiring derivatives

Parametric motion analysis (e.g., drones, projectiles)

Computational modeling of physical systems with constraints

Educational resource for learning differentiation programmatically
