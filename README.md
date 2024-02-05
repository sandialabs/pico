# Parallel Integer and Combinatorial Optimization Library (PICO)

Hart,William Eugene

SCR# 545

Parallel Integer and Combinatorial Optimization Library (PICO) Ver. 1.0 provides a framework for branch-and-bound, an intelligent enumeration search strategy that can be used to exactly solve integer and combinatorial optimization problems.  PICO encapsulates the functionality of branch-and-cut, and it provides flexible parameterization for level of interprocessor communication, workload distribution, branching search strategy (eager, lazy, hybrid), and choice of linear programming tool.  Additionally, PICO includes a custom scheduler to dynamically switch between `threads? of control that cooperatively share the CPU in limited operating system environments without system processes.  The modular design in PICO facilitates customization to include application-specific features like incumbent heuristics, and cutting planes.  PICO supports scalable parallel branch-and-bound on a wide range of computing platforms, using the portable communication library MPI.  Parallelization of serial branch-and-bound applications only requires the user specification of routines for packing and unpacking problem-specific data.

 

Parallel Integer and Combinatorial Optimization Library (PICO) Ver. 1.0 is a C++ library for scalable parallel branch-and-bound with application to mixed-integer linear programming.
