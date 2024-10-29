# mauro

[![Copier Badge][copier-badge]][copier-url]
[![Pixi Badge][pixi-badge]][pixi-url]
![License][license-badge]
[![CI Badge][ci-badge]][ci-url]
[![conda-forge Badge][conda-forge-badge]][conda-forge-url]
[![PyPI Badge][pypi-badge]][pypi-url]
[![Python version Badge][pypi-version-badge]][pypi-version-url]

Test package

## Development

This project is managed by [pixi](https://pixi.sh).
You can install the package in development mode using:

```bash
git clone https://github.com/maurosilber/mauro
cd mauro

pixi run pre-commit-install
pixi run test
```

### Publish to PyPI

When a tagged commit is pushed to GitHub,
the GitHub Action defined in `.github/workflows/CI.yml`
builds and publishes the package to PyPI.

Trusted publishing must be enabled in [PyPI](https://pypi.org).
Go to "Publishing" and fill the following values in the form:

```
PyPI Project Name: mauro
Owner: maurosilber
Repository name: mauro
Workflow name: ci.yml
Environment name: pypi
```

[ci-badge]: https://img.shields.io/github/actions/workflow/status/maurosilber/mauro/ci.yml
[ci-url]: https://github.com/maurosilber/mauro/actions/workflows/ci.yml
[conda-forge-badge]: https://img.shields.io/conda/vn/conda-forge/mauro?logoColor=white&logo=conda-forge
[conda-forge-url]: https://prefix.dev/channels/conda-forge/packages/mauro
[copier-badge]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-black.json
[copier-url]: https://github.com/copier-org/copier
[license-badge]: https://img.shields.io/badge/license-MIT-blue
[pixi-badge]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/prefix-dev/pixi/main/assets/badge/v0.json
[pixi-url]: https://pixi.sh
[pypi-badge]: https://img.shields.io/pypi/v/mauro.svg?logo=pypi&logoColor=white
[pypi-url]: https://pypi.org/project/mauro
[pypi-version-badge]: https://img.shields.io/pypi/pyversions/mauro?logoColor=white&logo=python
[pypi-version-url]: https://pypi.org/project/mauro
