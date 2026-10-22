# cuOpt
NVIDIA cuOpt is a high-performance, GPU-accelerated combinatorial optimization engine. Unlike traditional solvers strictly focused on CPUs (such as Gurobi or CPLEX in their default modes), which expend significant computational time trying to mathematically prove the exact optimal bound through complex Branch and Bound routines, cuOpt's MIP (Mixed-Integer Programming) module focuses its horsepower on hardware-accelerated primal heuristics. It utilizes a powerful combination of evolutionary algorithms, parallel domain propagation, and the Primal-Dual Hybrid Gradient (PDLP) method. This architecture allows to find extremely high-quality feasible solutions in fractions of a second, even for industrial-scale problems with millions of variables and constraints.


