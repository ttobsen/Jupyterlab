# Jupyterlab

Jupyterlab Docker Image. Use the `docker-compose.yml` as example for creating the Jupyterlab container.
The `jupyter_notebook_config.json` can be used to login into Jupyter with password `test123`.

## Mirrors

The repository is mirrored at [Gitlab](https://gitlab.com/Elpra/jupyterlab) and [Github](https://github.com/ttobsen/Jupyterlab).
Tags of the image can be found at [Docker Hub](https://hub.docker.com/r/elpra/jupyterlab).


## Packages

The image contains several different useful packages.

### jupytext

Jupytext is used to pair the `.ipynb` notebook files with a custom file type like `Markdown`. This is very
useful for versioning the notebooks using Git. See the [Jupytext Github Repo](https://github.com/mwouts/jupytext)
and [this](https://towardsdatascience.com/version-control-with-jupyter-notebooks-f096f4d7035a) site for further
information.

In general no further installation or setup is required for handling the large notebook files as Markdown.
