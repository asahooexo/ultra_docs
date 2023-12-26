Pre-install `conda` and `git` in your machine.

- Navigate to the directory you want to clone the repository into::

    $ cd /User/<YourUser>/repos/

- Before cloning this repository, follow the installation instructions for PASTIS: https://github.com/spacetelescope/PASTIS

- Create a new `ultra` conda environment using the `environment.yml` file present inside PASTIS repository::

    $ cd PASTIS
    $ conda env create --name ultra --file environment.yml

- Activate the conda environment::

    $ conda activate ultra


- Clone the `ULTRA` repository::

    $ git clone https://github.com/spacetelescope/ULTRA.git


- Update the newly created `ultra` conda environment with `environment.yml` file inside `ULTRA` repository::

    $ cd ULTRA
    $ conda env update --file environment.yml

- Install the `ULTRA` package into `ultra` environment in develop mode::

    $ python setup.py develop

- Install the `PASTIS` package into `ultra` environment in develop mode::

    $ cd PASTIS
    $ python setup.py develop


