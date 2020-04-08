# Contributing to CorpusCustody

Thanks for considering a contribution. CorpusCustody is an offline analyzer: it
reads manifests and never fetches or executes anything.

## Development setup

- Python 3.11+. The package uses the standard library only.

```bash
python -m compileall -q src
python -m pytest -q
PYTHONPATH=src python -m corpuscustody --help
