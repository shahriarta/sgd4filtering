# sgd4filtering
This is the repository for regenerating the simulations in the following work appeared in Neural Information Processing Systems (NeurIPS) 2023:\
"Data-driven Optimal Filtering for Linear Systems with Unknown Noise Covariances"\
by Shahriar Talebi $^{1,2} \quad$ Amirhossein Taghvaei $^{1}\quad$ Mehran Mesbahi $^{1}$\
  $^{1}$ University of Washington,
  Seattle, WA, 98105\
  $^{2}$ Harvard University, Cambridge, MA, 02138 \
  emails:  talebi@seas.harvard.edu $\quad$ amirtag@uw.edu $\quad$ mesbahi@uw.edu


**Abstract:** This paper examines learning the optimal filtering policy, known as the Kalman gain, for a linear system with unknown noise covariance matrices using noisy output data. The learning problem is formulated as a stochastic policy optimization problem, aiming to minimize the output prediction error. This formulation provides a direct bridge between data-driven optimal control and, its dual, optimal filtering. Our contributions are twofold. Firstly, we conduct a thorough convergence analysis of the stochastic gradient descent algorithm, adopted for the filtering problem, accounting for biased gradients and stability constraints. Secondly, we carefully leverage a combination of tools from linear system theory and high-dimensional statistics to derive bias-variance error bounds that scale logarithmically with problem dimension, and, in contrast to subspace methods, the length of output trajectories only affects the bias term.
