<p align="center">
  <img src="Store_Assets/Glossy%20Global%20Growth%20Analytics%20Icon-2.png" alt="EcoGraph Lab icon" width="150">
</p>

<h1 align="center">EcoGraph Lab</h1>

<p align="center">
  <strong>Version 51.3</strong><br>
  A Python desktop application for graph-based ecological and analytical workflows.
</p>

<p align="center">
  <a href="https://github.com/mominuorrahman-byte/EcoGraph-Lab/actions/workflows/ci.yml"><img src="https://github.com/mominuorrahman-byte/EcoGraph-Lab/actions/workflows/ci.yml/badge.svg?branch=main" alt="CI"></a>
</p>

## Overview

EcoGraph Lab is a desktop application distributed from this repository as a Python source project. The repository includes the application source, automated checks, and icon assets prepared for desktop packaging.

## Project status

- Current project version: **v51.3**
- Main source: `EcoGraphLab_v51_3.py`
- CI workflow: `.github/workflows/ci.yml`
- Icon assets: [`Store_Assets/`](Store_Assets/)

## Requirements

- Python 3.13
- The application and test dependencies listed in the CI workflow.

## Run from source

Create and activate a virtual environment, install the required dependencies, then run:

```bash
python EcoGraphLab_v51_3.py
```

Check the application version:

```bash
python EcoGraphLab_v51_3.py --version
```

Run the automated self-test in a headless environment:

```bash
QT_QPA_PLATFORM=offscreen python -u EcoGraphLab_v51_3.py --self-test
```

The CI workflow installs the Linux GUI runtime libraries required by Qt before running the checks.

## Screenshots

Application screenshots will be added to [`docs/screenshots/`](docs/screenshots/). Only genuine screenshots captured from the running application should be placed there.

## Repository layout

```text
.
├── .github/workflows/ci.yml
├── Store_Assets/
│   ├── EcoGraph_Store_300.png
│   ├── EcoGraph_Windows.ico
│   └── Glossy Global Growth Analytics Icon-2.png
├── docs/
│   └── screenshots/
├── EcoGraphLab_v51_3.py
└── README.md
```

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before proposing changes.

## License

No license has been specified in this repository yet. Until a license is added, do not assume that the source code may be reused, modified, or redistributed.
