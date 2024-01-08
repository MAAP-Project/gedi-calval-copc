# stactools-gedi-calval-copc

[![PyPI](https://img.shields.io/pypi/v/stactools-gedi-calval-copc?style=for-the-badge)](https://pypi.org/project/stactools-gedi-calval-copc/)
![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/stactools-packages/gedi-calval-copc/continuous-integration.yml?style=for-the-badge)

- Name: gedi-calval-copc
- Package: `stactools.gedi_calval_copc`
- [stactools-gedi-calval-copc on PyPI](https://pypi.org/project/stactools-gedi-calval-copc/)
- Owner: @githubusername
- [Dataset homepage](http://example.com)
- STAC extensions used:
  - [proj](https://github.com/stac-extensions/projection/)
- Extra fields:
  - `gedi-calval-copc:custom`: A custom attribute
- [Browse the example in human-readable form](https://radiantearth.github.io/stac-browser/#/external/raw.githubusercontent.com/stactools-packages/gedi-calval-copc/main/examples/collection.json)
- [Browse a notebook demonstrating the example item and collection](https://github.com/stactools-packages/gedi-calval-copc/tree/main/docs/example.ipynb)

A short description of the package and its usage.

## STAC examples

- [Collection](examples/collection.json)
- [Item](examples/item/item.json)

## Installation

```shell
pip install stactools-gedi-calval-copc
```

## Command-line usage

Description of the command line functions

```shell
stac gedi-calval-copc create-item source destination
```

Use `stac gedi-calval-copc --help` to see all subcommands and options.

## Contributing

We use [pre-commit](https://pre-commit.com/) to check any changes.
To set up your development environment:

```shell
pip install -e '.[dev]'
pre-commit install
```

To check all files:

```shell
pre-commit run --all-files
```

To run the tests:

```shell
pytest -vv
```

If you've updated the STAC metadata output, update the examples:

```shell
scripts/update-examples
```
