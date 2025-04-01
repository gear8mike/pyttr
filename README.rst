Implementation of TTR algorithm with python
===========================================

.. image:: https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr/badges/main/pipeline.svg
    :target: https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr/-/commits/main

.. image:: https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr/badges/main/coverage.svg
    :target: https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr/-/commits/main

.. image:: https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr/-/badges/release.svg
    :target: https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr/-/releases

.. .. image:: https://git.km3net.de/examples/km3badges/-/raw/master/docs-latest-brightgreen.svg
..     :target: https://neutrino.pages.km3net.de/pyttr


Installation
~~~~~~~~~~~~

It is recommended to create an isolated virtualenvironment to not interfere
with other Python projects, preferably inside the project's folder. First clone
the repository with::
.. code-block:: bash

  git clone git@gitlab.rrz.uni-hamburg.de:neutrino/pyttr.git

or::
.. code-block:: bash

  git clone https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr.git

Create and acitvate a virtual environment::
.. code-block:: bash  

  cd pyttr
  python3 -m venv venv
  . venv/bin/activate

Then install the package::
.. code-block:: bash

  make install

To install all the development dependencies, in case you want to contribute or
run the test suite::
.. code-block:: bash

  make install-dev
  make test

Currently this option is not available!
You can also install the package directly from ``Pypi`` via ``pip`` package manager (no cloning needed).
It can easily be done into any Python environment with next command::
.. code-block:: bash  

  pip install pyttr


---

*Created with ``cookiecutter https://git.km3net.de/templates/python-project``*
