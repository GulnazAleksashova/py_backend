==========================
FastAPI base project
==========================

Poetry initial setup
-------------------------------------------------------------------------------
- Configure Poetry **(should be done once globally)**:

.. code::

    poetry config virtualenvs.in-project false
    poetry config virtualenvs.path <conda-install-path>/envs

Packages installation
-------------------------------------------------------------------------------
- Create and activate *conda* virtual environment for development:

.. code::

    conda create -n myBaseApp python=3.8
    conda activate BaseApp

- Install dependencies with Poetry:

.. code::

    poetry install