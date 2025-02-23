# Tests

This directory contains tests and micro-benchmarks for pyribs. The tests mirror
the directory structure of `ribs`. To run these tests, install the dev
dependencies for ribs with `pip install ribs[dev]` or `pip install -e .[dev]`
(from the root directory of the repo).

For information on running tests, see [CONTRIBUTING.md](../CONTRIBUTING.md).

## Visualization Tests

We divide the visualization tests into `visualize` and `visualize_qdax`, where
`visualize_qdax` tests visualizations of QDax components.

## Additional Tests

This directory also contains:

- `examples.sh`: checks that the examples work end-to-end
- `tutorials.sh`: checks that the tutorials work end-to-end
