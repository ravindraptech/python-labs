# using-jupyter-notebook

## How to setup jupyter on local machine
ref: https://jupyter.org/install
$ pip install jupyterlab
$ jupyter lab
$ pip install notebook

## To run the jupyter notebook
$ jupyter notebook

- Default browser e.g. chrome will open with url: http://localhost:8888/tree

## Creating new notebook
1. From menu: File > New > Notebook
2. Select kernel = Pyton 3 (ipykernel)
3. Refer helloworld.ipynb (write code / markdown / raw)

## How do I start the Notebook using a custom IP or port?
By default, the notebook server starts on port 8888. If port 8888 is unavailable or in use, the notebook server searches the next available port. You may also specify a port manually. In this example, we set the server’s port to 9999:
$ jupyter notebook --port 9999

## Using a command-line interface
Notebooks can be executed from your terminal using the execute subcommand.
It expects notebook paths as input arguments and accepts optional flags to modify the default behavior.

$ jupyter execute notebook.ipynb

You can pass more than one notebook as well.
$ jupyter execute notebook.ipynb notebook2.ipynb

By default, notebook errors will be raised and printed into the terminal.
You can suppress them by passing the --allow-errors flag.

$ jupyter execute notebook.ipynb --allow-errors



