# Poetry 
This package is an example project for building a Python package (i.e. wheel or sdist).
It relies on [poetry](https://python-poetry.org) as a build backend with pyproject.toml
for configuration.

## Commands:

* Editable install:
```shell
poetry install
```
* Run code:
```shell
poetry run python -c "import demo"
```
* Build:
```shell
poetry build
``````
* Upload to PyPI:
```shell
poetry publish
```