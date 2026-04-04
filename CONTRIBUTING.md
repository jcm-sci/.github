# Contributing

Thank you for your interest in contributing!

## Getting Started

1. **Fork** the repository
2. **Clone** your fork locally
3. **Install** the development tools:
   - [uv](https://docs.astral.sh/uv/) — Python project manager
   - [just](https://just.systems/) — command runner
4. **Run** `just ci` to verify everything works

## Development

- Run `just` to see all available commands
- Run `just ci` before pushing (lint + typecheck + test)
- Follow the existing code style (enforced by linters)
- Add tests for new functionality
- Keep commits focused and well-described

## Pull Requests

- Create a feature branch from `main`
- Keep PRs focused on a single change
- All CI checks must pass before merge
