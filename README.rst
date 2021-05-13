Python template
========================

|Travis status| |Codecov status| |Apache license|

This repository contains a template for starting Python projects.

---------------

HOW TO USE THE PACKAGE
-----

The package is currently not distributed anywhere.

You can clone the repository and do the following:

1. Create virtual environment:

.. code-block:: bash

	$ cd <project-home>
	$ python3 -m venv .env

2. Activate virtual environment

.. code-block:: bash

	$ source .env/bin/activate

3. Update the pip distribution (to avoid potential issues)

.. code-block:: bash

	$ pip install --upgrade pip

4. Install package for testing in the virtual environment

.. code-block:: bash

	$ python3 setup.py develop

5. Import the package and use it!

---------------

DEPENDENCIES
-----

Insert your dependencies here.
The main package dependencies are numpy_, `scikit-learn <https://scikit-learn.org/>`_, etc. .

.. _numpy: https://numpy.org

.. |Travis status| image:: Insert Travis image

.. |Codecov status| image:: Insert Codecov image

.. |Apache license| image:: https://img.shields.io/badge/License-Apache%202.0-blue.svg
   :target: LICENSE
