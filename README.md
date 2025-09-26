# Sandpiper Food Search Algorithm (SFSA)

This project introduces the Sandpiper Food Search Algorithm (SFSA), a new bio-inspired metaheuristic optimization algorithm. SFSA is motivated by the food searching behavior of sandpipers on beaches, where each bird explores locally, adapts to environmental disturbances (waves), and shares only limited information with nearby neighbors. The algorithm is designed for complex systems where global knowledge is unrealistic, such as underground mining, spacecraft trajectory planning, and swarm robotics


## Project Objective

* Develop a biologically inspired algorithm with limited agent knowledge.
* Simulate sandpiper behavior with local neighbor sharing and wave-driven exploration.
* Benchmark SFSA against the Firefly Algorithm (FA) using four standard functions:
  * Ackley
  * Griewank
  * Holder Table
  * Rastrigin

## Key Features of SFSA

* Local knowledge: Agents communicate only with neighbors within a visibility radius.
* Staying duration: Tracks quality of solutions at a location.
* Wave action: Periodic environmental disturbance forcing exploration beyond local minima.
* Emergent behavior: Swarm clusters around optimal solutions without centralized control.

## Results

* Improved solution quality: SFSA outperformed FA on Ackley, Griewank, and Rastrigin by up to 17% in mean best solution
* Higher reliability: On average, SFSA was 38% more reliable at finding solutions within 95% of the global optimum.
* Efficiency: Although per-iteration runtime was longer, SFSA reached FA’s 100-iteration solutions in as few as 10 iterations.
* Trade-off: FA slightly outperformed SFSA on Holder Table, showing strengths vary by function.

Link to paper: https://doi.org/10.1115/DETC2024-142709
