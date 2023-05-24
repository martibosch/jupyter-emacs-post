# Jupyter in the Emacs universe

Example notebook used in the ["Jupyter in the Emacs universe"](https://martibosch.github.io/jupyter-emacs-universe) post.

## Instructions to reproduce

1. Clone the repository and change directory to the repository's root:

```bash
git clone https://github.com/martibosch/jupyter-emacs-post
cd jupyter-emacs-post
```

2. Create the environment (this requires conda/mamba) and activate it:

```bash
# replace conda for mamba if needed
conda env create -f environment.yml
conda activate jupyter-emacs
```

3. Register the IPython kernel of the `jupyter-emacs` environment

```bash
python -m ipykernel install --user --name jupyter-emacs --display-name "Python (jupyter-emacs)"
```

4. You can now execute the `notebook.ipynb` file.
