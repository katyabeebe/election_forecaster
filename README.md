# Election forecaster

This repository stores a model for forecasting multiparty elections.

# Project tree

 * [election_forecaster](./election_forecaster/) 
   * [model_outputs](./election_forecaster/model_outputs/)                                             
   * [results](./election_forecaster/results/)
   * [notebooks](./election_forecaster/scripts/)
      * [00_model.ipynb](./election_forecaster/scripts/00_model.ipynb)
      * [01_simulation_provincial.ipynb](./election_forecaster/scripts/01_simulation_provincial.ipynb)
      * [02_simulation_national.ipynb](./election_forecaster/scripts/01_simulation_national.ipynb)
      * [03_final_cleaning.ipynb](./election_forecaster/scripts/03_final_cleaning.ipynb)
 * [dev](./election_forecaster/dev/)
 * [raw_data](./raw_data/) 
 * [LICENSE](./LICENSE)
 * [makefile](./makefile)
 * [poetry.lock](./poetry.lock)
 * [pyproject.toml](./pyproject.toml)
 * [README.md](./README.md)

# Getting started

1. Use `pyenv` to run python version mentioned in `.python-version`
2. Install [poetry](https://poetry.eustace.io/docs/#installation) if necessary
3. Run `poetry install` to create virtual env
4. Run `poetry shell` to activate virtual env
