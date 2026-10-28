# CoWork Trial — Pictures

A minimal workspace for a picture-based trial. The repository intentionally starts with structure and documentation only; no product behavior, image format, processing pipeline, or tooling is assumed yet.

## Structure

- `pictures/input/` — source pictures used in the trial
- `pictures/output/` — generated or edited pictures produced by the trial
- `pictures/reference/` — optional visual references or comparison material
- `docs/SETUP.md` — minimal setup and working conventions
- `CONTRIBUTING.md` — contribution guidance

Each picture folder contains a `.gitkeep` placeholder so the directory exists before assets are added.

## Getting started

1. Clone the repository.
2. Read `docs/SETUP.md`.
3. Put source assets in `pictures/input/` and, when applicable, results in `pictures/output/`.
4. Add references to `pictures/reference/` only when they are useful to the trial.

## Assumptions

- This repository is for a picture-oriented trial, based only on its current title.
- Requirements, implementation language, frameworks, automation, and image-processing behavior are not yet defined.
- The scaffold should remain lightweight until those decisions are made.

When the trial's requirements become clearer, extend this structure rather than adding speculative infrastructure up front.
