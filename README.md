# model_predictive_control

[![codecov](https://codecov.io/gh/AdityaNG/model_predictive_control/branch/main/graph/badge.svg?token=model_predictive_control_token_here)](https://codecov.io/gh/AdityaNG/model_predictive_control)
[![CI](https://github.com/AdityaNG/model_predictive_control/actions/workflows/main.yml/badge.svg)](https://github.com/AdityaNG/model_predictive_control/actions/workflows/main.yml)

Python implementation of MPC solver

## Install it from PyPI

```bash
pip install model_predictive_control
```

## Usage

```py
# TODO
from model_predictive_control import BaseClass
from model_predictive_control import base_function

BaseClass().base_method()
base_function()
```

```bash
$ python -m model_predictive_control
#or
$ model_predictive_control
```

## Development

Read the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## TODO

- [ ] Bicycle Model
- [ ] Drone Model
- [ ] MPC
- [ ] Visualizer Demo

- [ ] MPC Auto-Optimizer: Takes a set of expected vehicle trajectories and the search space of hyperparamters and returns the list of optimal hyperparameters
- [ ] MPC Compiler: Takes the MPC model with a set of expected vehicle trajectories and produces numpy array a mapping from trajectory to control signals. This can be used with a cosine similarity logic to decide on control logic in real time.
