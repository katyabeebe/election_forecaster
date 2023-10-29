# Election forecaster

This repository stores a model for forecasting multiparty elections.

# Project tree

 * [election_forecaster](./election_forecaster/) 
   * [model_outputs](./election_forecaster/model_outputs/)                                             
   * [results](./election_forecaster/results/)
   * [notebooks](./election_forecaster/notebooks/)
      * [00_model.ipynb](./election_forecaster/notebooks/00_model.ipynb)
      * [01_simulations_provincial.ipynb](./election_forecaster/notebooks/01_simulations_provincial.ipynb)
      * [02_simulations_national.ipynb](./election_forecaster/notebooks/01_simulations_national.ipynb)
      * [03_final_cleaning.ipynb](./election_forecaster/notebooks/03_final_cleaning.ipynb)
 * [dev](./dev/)
 * [LICENSE](./LICENSE)
 * [poetry.lock](./poetry.lock)
 * [pyproject.toml](./pyproject.toml)
 * [README.md](./README.md)

# Getting started

1. Use `pyenv` to run python version mentioned in `.python-version`
2. Install [poetry](https://poetry.eustace.io/docs/#installation) if necessary
3. Run `poetry install` to create virtual env
4. Run `poetry shell` to activate virtual env
