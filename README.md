# ML-Lab-3-Non-linear-Dimensionality-Reduction---t-SNE-and-UMAP

## Notebook environment

The notebooks use the `Python (ML Lab 3)` Jupyter kernel. In this Codespace,
the project `.venv` reuses preinstalled Python packages to avoid duplicating
large ML dependencies. To set up the same kind of environment:

```bash
python3 -m venv --system-site-packages .venv
.venv/bin/python -m ipykernel install --user --name ml-lab-3 --display-name "Python (ML Lab 3)"
```

On a machine without the required packages preinstalled, create an isolated
environment and install them from `requirements.txt` before registering the
kernel:

```bash
python3 -m venv .venv
.venv/bin/python -m pip install -r requirements.txt
.venv/bin/python -m ipykernel install --user --name ml-lab-3 --display-name "Python (ML Lab 3)"
```

In VS Code, choose **Python (ML Lab 3)** from the notebook kernel picker.