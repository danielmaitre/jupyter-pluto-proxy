# Jupyter Server Proxy + Pluto.jl

Launch the awesome Pluto.jl Notebook from the Jupyter Lab `Launcher` or the Jupyter Classic `New` dropdown. This package was built using the [`jupyter-server-proxy` cookiecutter template](https://github.com/illumidesk/cookiecutter-jupyter-server-proxy).

## Launch

Take it for a spin with Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/illumidesk/jupyter-pluto-proxy/main?urlpath=pluto)

## Requirements

- [Python 3.6+](https://www.python.org/downloads/)
- [Docker](https://docs.docker.com/get-docker/)

## Launch

```bash
make build
```

The `make build` command creates your virtual environment with `virtualenv` and Python3, installs the required dependencies, and then launches your notebook with an arbritrary port with `repo2docker`.

## Credits

- [`jupyter-server-proxy`](https://github.com/jupyterhub/jupyter-server-proxy)
- [`Pluto.jl](https://github.com/fonsp/Pluto.jl)

## License

BSD 3-Clause
