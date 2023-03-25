# Python service cookiecutter

## Documentation

- [Cookiecutter](https://cookiecutter.readthedocs.io/en/stable/)

## Usage

Run `cookiecutter cookiecutter-python-service` and you'll be prompted to
complete project's data. e.g:

```bash
cookiecutter cookiecutter-python-service
project_name [service]: pyserv
project_slug [pyserv]: 
project_description [pyserv]: my python service
```

As a result a new project will be created:

```bash
tree -a pyserv/
pyserv/
├── .coveragerc
├── dev-requirements.txt
├── Dockerfile
├── .flake8
├── .github
│   └── workflows
│       └── build.yaml
├── .mypy
├── .pre-commit-config.yaml
├── .pylintrc
├── pyserv
│   ├── config.py
│   ├── __init__.py
│   └── main.py
├── README.md
├── requirements.txt
├── setup.py
├── tests
│   ├── __init__.py
│   └── main_test.py
└── tox.ini
```
