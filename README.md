# AllegroGraph Python Tutorials

## Getting Started

Welcome to the tutorials for AllegroGraph's python client. To run the notebooks we recommed you create a virtual environment using the following commands:

```shell
conda env create --file environment.yml
```

Then to launch the environment run:

```shell
conda activate ag-tutorial
```

Then to finally launch Jupyter Lab:

```shell
jupyter lab
```

## Notebooks

* [tutorial](tutorial.ipynb). This is the most thorough tutorial of using python with AllegroGraph and contains everything you need to know to get to know the ins and outs of AllegroGraph with Python.

* [agraph-python-demo](agraph-python-demo.ipynb). This is a much shorter demo of the most essential aspects of the python AllegroGraph client.

* [allegrograph-etl](allegrograph-etl.ipynb). This is a demo of how to read in files of any type and convert the data to triples. We also show how to link up multiple sources of data into a single connected graph.

* [rbac-permissions](rbac-permissions.ipynb). A demo of how to create and manage user and role permissions using the python client.

* [attribute-based-permissions](attribute-based-permissions.ipynb). A demo of the advanced security capabilities of triple attributes.
