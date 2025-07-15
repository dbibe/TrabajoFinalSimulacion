# Trabajo Final Simulacion
## Balanceador de Cargas

## Notebook Links

- [Simulation Development](https://github.com/dbibe/TrabajoFinalSimulacion/notebooks/simulation.ipynb)
- [Fitting](https://github.com/dbibe/TrabajoFinalSimulacion/notebooks/fit.ipynb)
- [Results Analysis](https://github.com/dbibe/TrabajoFinalSimulacion/notebooks/results.ipynb)

## Setting Up Enviroment

### Option A - Using poetry

Install poetry globally:

```bash
pip install poetry
```

Install dependencies, `poetry` will create a virtual environment for you:

```bash
poetry install
```

For using the virtual environment in `Jupyter Notebook` create a kernel:

```bash
poetry run python -m ipykernel install --user --name tp
```

> NOTE: you can change `tp6` to any other name you want.

### Option B - Using pip

Install dependencies:

```bash
pip install -r requirements.txt
```

For using the virtual environment in `Jupyter Notebook` create a kernel:

```bash
python -m ipykernel install --user --name tp
```