# Py-MMD-Tools

[![pytest](https://github.com/metno/py-mmd-tools/actions/workflows/tests.yml/badge.svg)](https://github.com/metno/py-mmd-tools/actions/workflows/tests.yml)
[![codecov](https://codecov.io/gh/metno/py-mmd-tools/branch/master/graph/badge.svg)](https://codecov.io/gh/metno/py-mmd-tools)

Python tools for MMD.

To run the tests locally:
```
export MMD_PATH=<PATH TO MMD REPO>
python -m pytest -v --cov=py_mmd_tools --cov=script --cov-report=term --cov-report=xml
```

Or:
```
./run_tests.sh
```
