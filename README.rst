Implementation of TTR algorithm with python
===========================================

.. image:: https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr/badges/master/pipeline.svg
    :target: https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr/pipelines

.. image:: https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr/badges/master/coverage.svg
    :target: https://neutrino.pages.km3net.de/pyttr/coverage

.. image:: https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr/-/badges/release.svg
    :target: https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr/-/releases

.. .. image:: https://git.km3net.de/examples/km3badges/-/raw/master/docs-latest-brightgreen.svg
..     :target: https://neutrino.pages.km3net.de/pyttr


Installation
~~~~~~~~~~~~

It is recommended to first create an isolated virtualenvironment to not interfere
with other Python projects::

  git clone https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr
  cd pyttr
  python3 -m venv venv
  . venv/bin/activate

Install directly from the Git server via ``pip`` (no cloneing needed)::

  pip install git+https://gitlab.rrz.uni-hamburg.de/neutrino/pyttr

Or clone the repository and run::

  make install

To install all the development dependencies, in case you want to contribute or
run the test suite::

  make install-dev
  make test


---

*Created with ``cookiecutter https://git.km3net.de/templates/python-project``*
