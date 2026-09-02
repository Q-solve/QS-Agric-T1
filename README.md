# Quantum-Hybrid Optimisation of Last-Mile Fertiliser Distribution

**The Challenge:** Delivering fertiliser to scattered farms is a logistical nightmare. Limited fleets, fluctuating depot stocks, strict delivery windows, and challenging rural road networks create an optimization problem too complex for standard computers to solve efficiently at scale.

**The Innovation:** Our team is bridging classical operations research with quantum mathematical programming. We deploy a quantum-hybrid algorithm to solve multi-depot, time-window constraints simultaneously.

**The Impact:** Faster delivery routes, lower fuel costs, guaranteed supply security for farmers, and a scalable blueprint for quantum-driven agricultural logistics.

## Solutions
1. We model the problem as MILP (Mixed-Integer Linear Programming) model and solve it. This is a classical approach (explores each combination one at a time until it gets the cheapest/best route).
2. Convert the problem into a QUBO (Quadratic Unconstrained Binary Optimization) model. This is the Quantum approach (Explores all combinations simultaneously).
