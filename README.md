# RL Sandbox

This repository contains a collection of Reinforcement Learning (RL) algorithms implemented in the form of Jupyter notebooks. It serves as a sandbox environment for experimenting with and understanding RL algorithms. The goal is to provide clean, easy-to-follow implementations with explanations in order to facilitate learning and experimentation in RL.

## Overview

Currently, the repository includes the following algorithms:

1. **Policy Gradient with Baseline** ([policy-gradient-baseline.ipynb](policy-gradient-baseline.ipynb))
   - This notebook implements the vanilla policy gradient algorithm with a baseline, which reduces the variance of the gradient estimates and leads to more stable learning.
   - The baseline is typically the state-value function, which helps in faster convergence.
2. **Trust Region Policy Optimization (TRPO)** ([trpo.ipynb](trpo.ipynb))
   - This notebook demonstrates the TRPO algorithm, which improves policy optimization by enforcing a trust region constraint, ensuring stable and monotonic policy updates.
   - TRPO is known for its reliability and effectiveness in complex RL environments.
## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Python 3.x](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/install)
- Recommended: A virtual environment such as [venv](https://docs.python.org/3/library/venv.html) or [conda](https://docs.conda.io/en/latest/).
