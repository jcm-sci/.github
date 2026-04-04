# Joshua C. Macdonald

Principled inference, simulation, and model criticism for decision-critical
scientific systems under partial observability.

## Focus Areas

- **Model criticism & evaluation** — structured observables, Pareto-optimal
  configuration selection, Bayesian stacking, proper scoring
- **Operator-partitioned solvers** — IMEX/PDE operator splitting, trait-structured
  dynamical systems
- **Bayesian latent variable models** — variational PCA, posterior predictive
  testing, rank selection
- **Infectious disease forecasting** — surveillance design, ensemble calibration,
  scenario modeling

## Packages

| Package | Language | Description |
|---------|----------|-------------|
| [model-criticism](https://github.com/jcm-sci/model-criticism) | Python | Observable-based model evaluation, Pareto optimization, Bayesian stacking |
| [ModelCriticism.jl](https://github.com/jcm-sci/ModelCriticism.jl) | Julia | Observable-based model evaluation, Pareto optimization, Bayesian stacking |
| [OpEngine.jl](https://github.com/jcm-sci/OpEngine.jl) | Julia | Operator-partitioned numerical solver (ODE + IMEX/PDE splitting) |
| [OpSystem.jl](https://github.com/jcm-sci/OpSystem.jl) | Julia | Declarative dynamical system specification compiler (YAML → callable) |

## Related Work (other orgs)

| Package | Org | Description |
|---------|-----|-------------|
| [VBPCApy](https://github.com/yoavram-lab/VBPCApy) | yoavram-lab | Variational Bayesian PCA with missing-data support |
| [pp-eigentest](https://github.com/yoavram-lab/pp-eigentest) | yoavram-lab | Posterior predictive eigenvalue rank testing |
| [op_engine](https://github.com/ACCIDDA/op_engine) | ACCIDDA | Operator-partitioned solver (Python) |
| [op_system](https://github.com/ACCIDDA/op_system) | ACCIDDA | System specification compiler (Python) |
