# Copilot instructions for Mergington High School Activities

This repository serves a small static site for school activities, backed by a Python API.

## Conventions

- Keep the front end framework-free: plain HTML, CSS and JavaScript in `src/static/`.
- Match the existing color palette and spacing in `src/static/styles.css`; do not introduce new fonts.
- Every activity card must stay keyboard reachable and keep its existing `aria-label`s.
- Python code lives in `src/`; keep functions small and add type hints.
- Do not change the public activity REST endpoints in `src/app.py` without updating the JavaScript that calls them.

## Working agreements

- Run the Python test suite with `pytest` before opening a pull request.
- Describe the user-visible effect of a change in the pull request body.
- Leave the repository's GitHub Actions workflows alone unless the change is about automation.
