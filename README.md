# VQE

Toy implementation of the Variational Quantum Eigensolver method in Python using
[Qiskit](https://qiskit.org/).

## Run

Dependencies are managed with [poetry](https://python-poetry.org/).

To configure the environment, run the following

```shell
$ poetry install
Updating dependencies
Resolving dependencies... (9.9s)

Writing lock file
```

Then to open the python notebook, run

```shell
$ poetry run jupyter notebook VQE.ipynb
...
[I 17:39:36.954 NotebookApp] Jupyter Notebook 6.1.4 is running at:
[I 17:39:36.955 NotebookApp] http://localhost:8888/...
...
```

Alternatively, a `requirements.txt` is also included to install the
dependencies using only `pip`. Read more about this [here](https://pip.pypa.io/en/stable/reference/pip_install/)
