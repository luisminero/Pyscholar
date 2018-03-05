.. _installation:

Installation
============

Requirements
------------

Pyscholar is required to have the following packages installed:

* `Python <https://www.python.org/download/releases/2.7/>`_ >=2.7

* `NetworkX <https://networkx.github.io/documentation/>`_

  .. code-block:: console

     pip install networkx

* `Matplotlib <https://matplotlib.org/users/installing.html>`_

  .. code-block:: console

     pip install matplotlib

* `Pandas <http://pandas.pydata.org/pandas-docs/stable/install.html>`_

  .. code-block:: console

     pip install pandas

.. note:: Pyscholar does not support Python 3.x

Step-by-Step Installation Guide
-------------------------------

Before installing Pyscholar you must get your API Key from the following `link <http://dev.elsevier.com/myapikey.html>`_.

Once you have the API key. We continue with the installation of Pyscholar.

1. Clone the repository first as follows:

.. code-block:: console

   $ git clone https://github.com/rfabila/Pyscholar.git

2. Then you must run setup.py and enter your API key:

.. code-block:: console

   $ python setup.py
   $ Your Scopus API key: (Here you enter your API key)

3.  Finally we can check the installation by doing the following:

    * Navigate to the installation directory from the command line.

      .. code-block:: console
		      
	 $ cd ~/Pyscholar/src
   
    * Execute a Python `REPL <https://en.wikipedia.org/wiki/REPL>`_
      with the :command:`python` or :command:`ipython` commands, for example:

      .. code-block:: console

	 $ python
	 Python 2.7.6 (default, Jun 22 2015, 17:58:13) 
	 [GCC 4.8.2] on linux2
	 Type "help", "copyright", "credits" or "license" for more information.
	 >>>
	 
    * Now we just need to import the package:

      .. code-block:: python

	 >>> import pyscholar

If ``import pyscholar`` didn't fail, then the installation was successful.

