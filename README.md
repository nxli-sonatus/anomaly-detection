
# Anomaly Detection in Vehicle Data

This repository contains the anomaly detection pipeline on the vehicle data.

## Structure

- ml_data: handling data processing, transformation, etc.
- ml_evaluate: consist of generic evaluation utilities.
- ml_core: backend models, foundational components.
- ml_deploy: generic model conversion and optimization.
- ml_product: main products will be developed here. For example, anomaly detection.

## Setup

### Python dependency management with poetry
We use poetry to manage the python dependency in this repo
Here is the comparison between conda and poetry if you want to know why poetry is used here [link](https://medium.com/@life-is-short-so-enjoy-it/what-is-difference-between-conda-and-poetry-when-to-use-conda-over-poetry-8743cc49ce4f)
For Mac, follow the instructio [here](https://python-poetry.org/docs/#installing-with-pipx)

### Configuration with Hydra
We use Hydra to config the repor for configuring the model building, experiments. etc.
See [here](https://hydra.cc/docs/intro/) for a brief introduction to Hydra.
