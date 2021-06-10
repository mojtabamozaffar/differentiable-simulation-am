![supported python versions](https://img.shields.io/badge/python-%3E%3D%203.6-306998)
![dependencies status](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen)
![license MIT](https://img.shields.io/badge/licence-MIT-green)

# Differentiable Simulation for Additive Manufacturing

This repo contains a differentiable physics-based simulation tool. It focuses on additive manufacturing and uses gradient-based methods to optimize the process. Current version is developed on top of [Taichi](https://github.com/taichi-dev/taichi), which showed better performance compared to TensorFlow, PyTroch, and Jax in our tests.

## Features
* [x] Explore different automatic differentiation libraries
* [x] Automatic mesh and toolpath loader
* [X] Visualization tools using pyvista
* [ ] Upgrade for unstructured shape functions
* [ ] Validate results with benchmarks

## Demo

Thermal simulation results during the build:

![thermal simulation results](https://github.com/mojtabamozaffar/differentiable-simulation-am/blob/main/image/animation.gif)

Laser power evolution during optimization process:

![optimization results](https://github.com/mojtabamozaffar/differentiable-simulation-am/blob/main/image/result_caseII.png)


## Getting started
### Installation

```
git clone https://github.com/mojtabamozaffar/differentiable-simulation-am
cd differentiable-simulation-am

pip install -r requirements.txt
```

### Usage

Execute jupyter notebook cells sequentially, unless instructed in the comments.

## License

This project is released under the [MIT License](https://github.com/mojtabamozaffar/differentiable-simulation-am/blob/main/LICENSE).
