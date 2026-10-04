# Quantum Computing Projects

This repository is a collection of experiments, tutorials, and small projects built with [Qiskit](https://qiskit.org/). Each project is kept modular so that new algorithms, notebooks, and supporting files can be added over time.

## Projects

| Project          | Description                                                     | Main file                                        |
| ---------------- | --------------------------------------------------------------- | ------------------------------------------------ |
| Grover's Search  | Demonstration of Grover's quantum search algorithm.             | [`Grovers_Search.ipynb`](./Grovers_Search.ipynb) |
| Shor's Algorithm | Exploration of Shor's algorithm and quantum factoring concepts. | [`Shors_Code.ipynb`](./Shors_Code.ipynb)         |
## Getting started

### Requirements

- Python 3.9 or newer
- Jupyter Notebook or JupyterLab
- Qiskit

### Installation

Create and activate a virtual environment, then install the required packages:

```bash
python -m venv .venv
source .venv/bin/activate        # macOS/Linux
# .venv\Scripts\activate        # Windows

python -m pip install --upgrade pip
python -m pip install qiskit jupyter
```

Launch the notebooks with:

```bash
jupyter notebook
```

Or use JupyterLab:

```bash
jupyter lab
```

