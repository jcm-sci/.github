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

| Package                                               | Language | Description                                                                                                                   |
| ----------------------------------------------------- | -------- | ----------------------------------------------------------------------------------------------------------------------------- |
| [trade-study](https://github.com/jcm-sci/trade-study) | Python   | Released design and evaluation framework with protocol-driven simulators, proper scoring rules, Pareto analysis, and stacking |

## Inactive Design Scaffolds

The following repositories contain placeholder modules rather than usable
implementations. They are retained only as possible starting points for future
Julia work and should not be installed as packages.

| Repository                                                    | Status                                                       |
| ------------------------------------------------------------- | ------------------------------------------------------------ |
| [TradeStudy.jl](https://github.com/jcm-sci/TradeStudy.jl)     | Inactive scaffold for a possible `trade-study` port          |
| [OpSystem.jl](https://github.com/jcm-sci/OpSystem.jl)         | Inactive scaffold for a possible `op_system` port            |
| [OpEngine.jl](https://github.com/jcm-sci/OpEngine.jl)         | Inactive scaffold for a possible `op_engine` port            |
| [ScoringRules.jl](https://github.com/jcm-sci/ScoringRules.jl) | Inactive scaffold; no scoring-rule implementation is present |

## Related Work (other orgs)

| Package                                                        | Org         | Description                                                                                         |
| -------------------------------------------------------------- | ----------- | --------------------------------------------------------------------------------------------------- |
| [VBPCApy](https://github.com/yoavram-lab/VBPCApy)              | yoavram-lab | Variational Bayesian PCA for incomplete data with full posterior uncertainty                        |
| [pp-eigentest](https://jcmacdonald.dev/projects/pp_eigentest/) | yoavram-lab | Private pre-release work on posterior-predictive signal-rank selection                              |
| [op_engine](https://github.com/ACCIDDA/op_engine)              | ACCIDDA     | Array-API-aware operator-partitioned solver with explicit, IMEX, implicit, and stochastic methods   |
| [op_system](https://github.com/ACCIDDA/op_system)              | ACCIDDA     | Restricted expression parser and typed-IR compiler for structured dynamical systems                 |
| [flepimop2](https://github.com/ACCIDDA/flepimop2)              | ACCIDDA     | Configuration-driven orchestration and provider framework for infectious-disease modeling campaigns |
