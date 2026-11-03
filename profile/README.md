# jcm-sci

Research software for mechanistic simulation, statistical inference, and the
design of experiments, studies, monitoring programs, and surveillance. Applications
span human infectious disease, livestock and wildlife health, ecology, and earth
and environmental systems, especially when observations are incomplete. Maintained
by [Joshua C. Macdonald](https://jcmacdonald.dev/).

[Website](https://jcmacdonald.dev/) · [Publications](https://jcmacdonald.dev/publications/) · [Projects](https://jcmacdonald.dev/projects/)

## Focus Areas

- **Simulation and model specification.** Mechanistic models, numerical solvers and
  scientific machine learning across within-host, population, spatial and ecological scales
- **Inference and measurement.** Parameter estimation, incomplete-data models and
  checks of what observations can distinguish
- **Model evaluation and study design.** Prediction checks and comparisons of
  experiments, interventions, monitoring programs and surveillance plans

## Research in progress

Current methodological work includes empirical evaluation of scenario-model
submissions, parameter inference and calibration, and learning from sparse
observations. Declared consistency checks are evaluated for usefulness; they do not
by themselves establish predictive accuracy. [op_infer](https://jcmacdonald.dev/projects/inference_calibration/)
connects Bayesian fitting, simulation-based checks and replicated studies;
the source is public, pre-alpha and unreleased on PyPI while broader interfaces
and application-specific validation develop. See the
[research summaries](https://jcmacdonald.dev/projects/current_analyses/) and
[inference project](https://jcmacdonald.dev/projects/inference_calibration/) for
questions, aims and current status, with public papers and artifacts linked
where available.

## Packages

| Package                                               | Language | Description                                                                                                                                      |
| ----------------------------------------------------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| [trade-study](https://github.com/jcm-sci/trade-study) | Python   | Released framework for comparing model settings, experiments, studies and surveillance plans through replicated studies, paired comparisons, Pareto analysis and provenance-checked result bundles |

<!-- software-release:trade_study:start -->

Public alpha release: [v0.6.0 on PyPI](https://pypi.org/project/trade-study/0.6.0/). Cite the [v0.6.0 archive](https://doi.org/10.5281/zenodo.23497881); the [concept DOI](https://doi.org/10.5281/zenodo.19599838) covers all archived versions.

<!-- software-release:trade_study:end -->

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

| Package                                                             | Org         | Description                                                                                                                                                              |
| ------------------------------------------------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [VBPCApy](https://github.com/yoavram-lab/VBPCApy)                   | yoavram-lab | Variational Bayesian PCA for explicitly masked observations with approximate variational-posterior covariance summaries                                                                                      |
| [pp-eigentest](https://jcmacdonald.dev/projects/pp_eigentest/)      | yoavram-lab | Private pre-release work on posterior-predictive signal-rank selection                                                                                                   |
| [op_engine](https://github.com/ACCIDDA/op_engine)                   | ACCIDDA     | Released PDE/field and nonlocal operator core with deterministic/stochastic reaction solvers, independent NumPy SSA banks, named observations and qualified CPU backends |
| [op_system](https://github.com/ACCIDDA/op_system)                   | ACCIDDA     | Released PDE/field, nonlocal and reaction model compiler with Array API evaluators, reaction/observable metadata, forcing schedules and independent-block contracts      |
| [op_infer](https://github.com/ACCIDDA/op_infer)                      | ACCIDDA     | Public pre-alpha statistical layer for Bayesian fitting, simulation-based calibration and replicated study-design checks; unreleased on PyPI                             |
| [flepimop2](https://github.com/ACCIDDA/flepimop2)                   | ACCIDDA     | Configuration-driven orchestration and provider framework for infectious-disease modeling campaigns                                                                      |

The Python [op_system](https://accidda.github.io/op_system/latest/guides/capabilities/)
and [op_engine](https://accidda.github.io/op_engine/latest/guides/capabilities/) cores
can run independently of FlepiMoP2; separate provider packages connect the layers.
[trade-study's worked examples](https://jcm-sci.github.io/trade-study/guide/capabilities/)
show replicated evaluation and decision reporting. Qualification is specific to
the model, method and backend; a Pareto front or model weighting does not by
itself establish calibration or transfer to real data.
