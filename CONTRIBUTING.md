# Contributing to EcoGraph Lab

Thank you for your interest in improving EcoGraph Lab.

## Before making changes

1. Check existing issues and discussions to avoid duplicating work.
2. Keep changes focused and explain the problem they solve.
3. Avoid committing generated build output, virtual environments, caches, or private credentials.

## Development setup

Use Python 3.13 and create a virtual environment. Install the dependencies listed in `.github/workflows/ci.yml`.

## Checks before submitting

Run these checks from the repository root:

```bash
python -m py_compile EcoGraphLab_v51_3.py
python EcoGraphLab_v51_3.py --version
QT_QPA_PLATFORM=offscreen python -u EcoGraphLab_v51_3.py --self-test
```

For GUI changes, also launch the application and manually verify the affected screens on the target operating system.

## Pull requests

- Describe the motivation and user-visible impact.
- List the checks you ran and their results.
- Include genuine before/after screenshots for visual changes, when practical.
- Do not claim tests passed unless they were actually run.
