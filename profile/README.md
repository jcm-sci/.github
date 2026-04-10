# [Joshua C. Macdonald](https://jcmacdonald.dev/)

Decision support and principled inference for partially observed systems
across earth, environmental, and health sciences — determining what actions
to take, what experiments to run, and what measurements are worth collecting
when interventions are costly and uncertainty is unavoidable.

[Website](https://jcmacdonald.dev/) · [Publications](https://jcmacdonald.dev/publications/) · [Projects](https://jcmacdonald.dev/projects/)

## Focus Areas

- **Decision support under partial observability** — surveillance design,
  forecasting pipelines, intervention evaluation, resource allocation
- **Model criticism & evaluation** — structured observables, Pareto-optimal
  configuration selection, Bayesian stacking, proper scoring rules
- **Scientific AI/ML** — physics-embedded surrogates, lawful learning,
  generative model design
- **Operator-partitioned solvers** — IMEX/PDE operator splitting, trait-structured
  dynamical systems
- **Bayesian latent variable models** — variational PCA, posterior predictive
  testing, rank selection
- **Operational forecasting** — infectious disease scenario modeling,
  ensemble calibration, intervention timing

## Packages

| Package                                                           | Language | Description                                                                                            |
| ----------------------------------------------------------------- | -------- | ------------------------------------------------------------------------------------------------------ |
| [trade-study](https://github.com/jcm-sci/trade-study)     | Python   | Model evaluation and decision support: protocol-driven simulators, proper scoring rules, Pareto optimization, Bayesian stacking |
| [TradeStudy.jl](https://github.com/jcm-sci/TradeStudy.jl) | Julia    | Julia implementation of the trade-study framework with native scoring rules and global sensitivity analysis |
| [OpSystem.jl](https://github.com/jcm-sci/OpSystem.jl)             | Julia    | Declarative specification language and compiler for structured dynamical systems                        |
| [OpEngine.jl](https://github.com/jcm-sci/OpEngine.jl)             | Julia    | Operator-partitioned ODE/PDE solver with explicit, IMEX, and fully implicit methods                    |

## Related Work (other orgs)

| Package                                                     | Org         | Description                                                           |
| ----------------------------------------------------------- | ----------- | --------------------------------------------------------------------- |
| [VBPCApy](https://github.com/yoavram-lab/VBPCApy)           | yoavram-lab | Variational Bayesian PCA for incomplete data with full posterior uncertainty |
| [pp-eigentest](https://github.com/yoavram-lab/pp-eigentest) | yoavram-lab | Posterior predictive eigenvalue testing for signal rank determination |
| [op_engine](https://github.com/ACCIDDA/op_engine)           | ACCIDDA     | Operator-partitioned ODE/PDE solver core (Python)                    |
| [op_system](https://github.com/ACCIDDA/op_system)           | ACCIDDA     | Declarative specification language and compiler (Python)             |
| [flepimop2](https://github.com/ACCIDDA/flepimop2)           | ACCIDDA     | Configuration-driven forecasting orchestration engine                |
