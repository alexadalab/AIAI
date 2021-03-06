# AIAI

Alexandra Institute Artificial Intelligence, a Python package for Danish data science.

Developers:

- Dan Saattrup Nielsen (dan.nielsen@alexandra.dk)
- Anders Jess Pedersen (anders.j.pedersen@alexandra.dk)


## Setup

### Set up the environment

1. Run `make install`, which installs Poetry (if it isn't already installed), sets up a virtual environment and all Python dependencies therein.
2. Run `source .venv/bin/activate` to activate the virtual environment.

### Install new packages

To install new PyPI packages, run:

```bash
poetry add <package-name>
```

### Auto-generate API documentation

To auto-generate API document for your project, run:

```bash
make docs
```

To view the documentation, run:

```bash
make view-docs
```

## Project structure
```bash
.
├── .flake8
├── .github
│   └── workflows
│       └── ci.yml
├── .gitignore
├── .pre-commit-config.yaml
├── LICENSE
├── README.md
├── data
│   ├── final
│   │   └── .gitkeep
│   ├── processed
│   │   └── .gitkeep
│   └── raw
│       └── .gitkeep
├── docs
│   └── .gitkeep
├── makefile
├── models
│   └── .gitkeep
├── notebooks
│   └── .gitkeep
├── poetry.toml
├── pyproject.toml
├── src
│   ├── scripts
│   │   └── fix_dot_env_file.py
│   └── aiai
│       └── __init__.py
└── tests
    └── __init__.py
```
