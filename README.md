# Logistic Regression with Sklearn a Dash front end deployed with Docker 

**Powered by:**

[![Python](https://img.shields.io/pypi/pyversions/tensorflow?logo=python&logoColor=white)](https://github.com/python/cpython)
[![Numpy](https://img.shields.io/badge/Numpy-1.19.5-skyblue?logo=numpy)](https://github.com/numpy/numpy)
[![Dash](https://img.shields.io/badge/Dash-1.18.1-blue)](https://github.com/plotly/dash)
[![Sklearn](https://img.shields.io/badge/scikit%20learn-0.24.0-orange)](https://github.com/scikit-learn/scikit-learn)
[![Docker](https://img.shields.io/badge/Docker-20.10.2-blue?logo=docker)](https://github.com/docker)
[![DVC](https://img.shields.io/badge/DVC-1.11.10-purple?logo=dvc)](https://github.com/iterative/dvc)
[![aws](https://img.shields.io/badge/AWS-ECS-orange?logo=aws)](https://aws.amazon.com/)
[![aws](https://img.shields.io/badge/AWS-S3-orange?logo=aws)](https://aws.amazon.com/)
[![Black](https://img.shields.io/badge/Code%20Style-Black-black)](https://github.com/psf/black)

## What is it?

A Dash App that classifies risky vehicle loan transactions, the model was trained with a Logistic Regresion from scikit-learn on the Kaggle Vehicle Loan Default Dataset.
Data is stored in an S3 bucked and versioned using DVC, the model is Dockerized and delpoyed on the cloud.

Demo site: To be deployed

Model training notebook is included. You can either use the included pickle file or train your own with the notebook. 

## Installation

If you want to use it as the base for your own project you can do it by following the below instructions.

Requirements:

- Git
- Python 3.8.X or higher with pip3 installed
- See requirements.txt for dependencies

Clone the repository into any directory you want by doing:

```bash
git clone https://github.com/techno1731/RFR_Sklearn_Dash.git
```
then cd into the RFR_Sklearn_Dash folder and remove all git files. Linux example below:

In Linux or any UNIX like bash shell:

```bash
rm -rf .git*
```
Change into your virtual environment or create one for this project with your favorite tool, pyenv, venv, virtualenv, etc.

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install pip-tools.

```bash
pip install pip-tools
```
Then install the requirements into your virtual environment (recommended) by doing:

```bash
pip-sync
```
That's it you have an environment ready to develop with the codebase.

## Usage

To run the application locally after following installation instructions do:

```bash
python run.py
```
Play with the sliders to observe how the the predicted MPG changes.

## License
[MIT](https://choosealicense.com/licenses/mit/)
