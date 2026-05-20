# AGENTS.md

Scope: entire repository.

## Project conventions
- Keep all original notebook content intact. When updating notebooks, only append new cells or add new lines without deleting existing text/code.
- Prefer local, reproducible execution with a `uv`-managed virtual environment.
- Store reusable Python dependencies in `pyproject.toml`.

## Notebook editing guidance
- Do not remove or rewrite the original assignment narrative.
- Add setup notes for both local `uv` execution and Colab where helpful.
- Keep data file paths configurable (e.g., via variables) when adding new code.

## Validation
- Run a lightweight sanity check for JSON validity after notebook edits.
