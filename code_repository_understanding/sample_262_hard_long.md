# Metadata

- ID: 6708ae87bb02136c067d1847
- Domain: Code Repository Understanding
- Subdomain: Code repo QA
- Difficulty: hard
- Length: long

# Question

Alpa is a module designed for automatic model parallel training. During the compilation process in Alpa, an important step is **layer construction**, where the training function's jaxpr is divided into a series of pipeline layers. Alpa employs a dynamic programming algorithm during this layer splitting process, which heuristically ensures that the computation load of each layer is approximately balanced while minimizing the communication cost between layers. In summary, what kind of optimization problem is this dynamic programming algorithm trying to solve? (hint: look at alpa/pipeline_parallel/layer_construction::cluster_jaxpr_by_cost)

Notation:
- \( C \) represents the communication cost
- \( f \) represents the computation load
- \( L \) represents the total number of pipeline layers
- \( \delta \) and \( \theta \) are hyperparameters

# Choices

- A: \min \text{Var}(f_1, \cdots, f_L) + \delta C
- B: \min \frac{|\max(f_1, \cdots, f_L) - \min(f_1, \cdots, f_L)|}{\text{avg}(f_1, \cdots, f_L)} + \delta C
- C: \min C 
\quad \text{s.t.} \quad f_i \leq (1 + \delta) \, \text{avg}(f_1, \cdots, f_L)
- D: \min \text{Var}(f_1, \cdots, f_L) + \theta C 
\quad \text{s.t.} \quad f_i \leq (1 + \delta) \, \text{avg}(f_1, \cdots, f_L)

# Answer

C
